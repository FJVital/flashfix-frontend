# flashfix.io Frontend

This repository contains the frontend interface and landing page for **flashfix.io**, a streamlined web application designed to automatically map, clean, and format raw supplier CSV files into pristine, ready-to-import Shopify product files.

## Overview
The frontend is designed to be lightning-fast, user-friendly, and transparent. It features a drag-and-drop interface for users to upload their supplier files and preview a 20-row sample of the AI-processed output before committing to payment.

**Key Frontend Features:**
* Drag-and-drop CSV upload zone.
* Dynamic, in-browser data preview table for mapped results.
* Secure payment gateway integration via Stripe.
* Cloud vault history dashboard for registered members to access processed files.

## Architecture
This repository contains purely frontend code (HTML, CSS, Vanilla JavaScript). It is hosted via GitHub Pages and handles the user interface and client-side routing. 

All heavy lifting, AI processing, data parsing, and secure file storage are handled by an isolated, containerized Python backend engine running on Render. No data is stored, trained, or processed on the client side.

## Support
For any questions, issues, or refund requests, please contact the engineering team at support@flashfix.io.
