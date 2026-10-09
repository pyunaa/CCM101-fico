# Multi-Tier Architecture

## What Is a Two-Tier Architecture?

A two-tier architecture is an application design that separates an application into two main parts: the web/application tier and the database tier. These tiers communicate with each other to provide services to users.

## The Web/Application Tier

The web/application tier handles user requests and displays the application's interface through a web browser. In this project, Nextcloud provides the interface that allows users to access and manage their files through a private cloud storage system.

## The Database Tier

The database tier stores and manages persistent information, such as user accounts, settings, and file metadata. In this project, MariaDB serves as the database for Nextcloud.

## Why Separate Them?

Separating the web application and database into different containers makes the system easier to manage, maintain, and troubleshoot. Each container can be updated or configured independently, and the database is separated from the public-facing web application. Docker Compose allows both containers to communicate through a shared application network.
