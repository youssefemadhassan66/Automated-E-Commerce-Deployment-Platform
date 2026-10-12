# Automated E-Commerce Deployment Platform

> DEPI DevOps Track: Graduation Project

## Overview

The **Automated E-Commerce Deployment Platform** is a complete, real-world style online store together with the automated system that builds, tests, deploys, and monitors it.

The project has two sides that work together:

1. **The application**: an e-commerce web store for gaming PCs, laptops, and computer components, including a custom PC builder.
2. **The platform**: the DevOps pipeline and cloud infrastructure that take every code change from a developer's machine to a live, running, and monitored deployment with no manual steps.

The goal is not only to build a working store, but to show how modern software teams ship software: small changes, automated checks, repeatable infrastructure, and full visibility into what is running in production.

## The Problem

Many small online stores are deployed by hand: someone copies files to a server, restarts it, and hopes nothing breaks. This leads to:

- Slow and risky releases
- "It works on my machine" problems
- Servers that nobody can rebuild if they fail
- No warning when the site is slow, down, or running out of stock

## Our Solution

We build the store as a set of small, independent services and wrap it in an automated delivery pipeline:

- **Containerization**: every part of the application runs in its own container, so it behaves the same on every machine.
- **Continuous Integration**: every change is automatically tested and built before it can be merged.
- **Continuous Delivery**: approved changes are automatically packaged and deployed to the cloud.
- **Infrastructure as Code**: the cloud servers and their setup are described in code, so the whole environment can be created or rebuilt with one command.
- **Orchestration**: the services run on Kubernetes, which restarts failed parts and scales them when traffic grows.
- **Monitoring & Alerting**: dashboards show the health of the system, and alerts fire when something goes wrong (errors, slow responses, low stock).

## Application Features

**For customers**
- Browse and search PCs, laptops, and components with filters
- Product pages with options (memory, storage, color) and live stock
- PC Builder that checks part compatibility and power requirements
- Shopping cart and checkout
- Account, order history, and order tracking

**For the store team**
- Separate roles for customers, staff, and admins
- Admin panel to manage products, prices, stock, orders, and users
- Full history of every stock change
- Automatic low-stock alerts

## Project Objectives

- Build a functional e-commerce application with a clean, modular design
- Automate the full path from code commit to production deployment
- Provision cloud infrastructure entirely through code
- Run the application in a self-healing, scalable environment
- Provide real-time monitoring, logging, and alerting
- Practice a professional team workflow: branches, pull requests, and code reviews

## Team Workflow

- Work is split into small, focused pull requests: one specific part at a time
- All changes go through a development branch and are reviewed before merging
- The main branch always holds a stable, releasable version

## Team

- Youssef Emad Hussin
- Omar Mohamed Mohamed
- Abdelrahman Nasser Fathi Elsayed

## Status

In progress. The project is being built step by step.
