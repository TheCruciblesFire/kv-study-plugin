# KV Devotion Plugin

Production release: **1.1.1**

Runtime path: `plugins/kv-devotion-plugin/`  
Marketplace manifest: `.agents/plugins/marketplace.json`

This repository is the GitHub-managed distribution source for **KV Devotion Plugin**.

The runtime contains the `kv-devotion-builder` core Skill plus seven bounded supporting Skills. Research and full passage study remain upstream in KV Study Plugin. Sermon, course, final media, platform packaging, scheduling, and publishing remain downstream.

## Existing Workspace plugin takeover

Existing Workspace plugin ID:

`Plugin_b506dabc2380819190fad684064528d6`

The marketplace entry includes this value as `pluginId`. When this marketplace is imported into the same ChatGPT workspace, GitHub should become the source for the existing Workspace plugin instead of creating a second plugin. The plugin name in the marketplace and runtime remains `kv-devotion-plugin`.

## Release discipline

Do not edit a released runtime in place. Functional changes should use a new plugin version and rerun the relevant validation/regression checks before GitHub sync.
