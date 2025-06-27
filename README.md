# 🕒 MCP Cron Actions – Automated API Triggers via GitHub Actions

This repository automates scheduled API calls to the MCP (Model Control Protocol) server using GitHub Actions. Each workflow triggers a specific route on a staggered schedule (every 8 minutes) starting at **11:00 PM IST (17:30 UTC)** daily to avoid database contention or deadlocks.
