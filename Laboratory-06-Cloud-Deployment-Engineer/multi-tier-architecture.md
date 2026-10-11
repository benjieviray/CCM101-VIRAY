# Multi-Tier Architecture

## What is a Two-Tier Architecture?

A two-tier architecture is an application structure that separates the web/application tier from the database tier. In this laboratory activity, Nextcloud serves as the web application, while MariaDB stores the application's data.

## The Web/Application Tier

The web/application tier uses Nextcloud to provide the user interface and handle requests from users through a web browser. It allows users to access their private cloud storage through the web.

## The Database Tier

The database tier uses MariaDB to store persistent application data, including user account information and file metadata. It helps Nextcloud manage and retrieve the information it needs.

## Why Separate Them?

Separating the web application and database into two containers makes the system easier to manage, maintain, and troubleshoot. Each service can be configured and updated independently, while Docker Compose helps connect the containers into one application.
