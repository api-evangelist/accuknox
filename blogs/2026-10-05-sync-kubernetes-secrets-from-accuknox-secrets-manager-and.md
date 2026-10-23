---
title: "Sync Kubernetes Secrets from AccuKnox Secrets Manager and Rotate them with no Code Changes"
url: "https://accuknox.com/blog/secrets-manager-sync-rotate-kubernetes-secrets"
date: "2026-10-05"
author: "Atharva Shah"
feed_url: "https://accuknox.com/blog/feed/"
---
An External Secret object copies a password from AccuKnox Secrets Manager into a Kubernetes secret every 10 seconds. WordPress keeps reading the same secret, so its code never changes.
