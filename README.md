# Next.js 15 App Router Link Issue

This repository demonstrates a potential issue with the Next.js 15 App Router and the `Link` component.  The issue seems to be related to how the App Router handles client-side navigation when using links within the component.

## Problem

The provided `MyComponent` contains two `Link` components.  In a correctly functioning app, clicking these links should navigate the user to `/` and `/about` respectively. However, this is not happening correctly. This issue is especially noticeable during development and after deployment.

## Solution

The solution involves ensuring that your `Link` components are correctly configured.  This might involve checking for typos in your paths or verifying your routing setup.

## Setup

1. Clone this repository
2. Navigate to the repository in your terminal
3. Run `npm install` to install dependencies.
4. Run `npm run dev` to start the development server.
5. Observe the unexpected behavior of links.