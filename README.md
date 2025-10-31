# Byzantine Generals Problem Simulation

A web-based interactive simulation of the Byzantine Generals Problem, demonstrating consensus algorithms in distributed systems with malicious actors.

## Overview

This simulation visualizes the classic computer science problem where a group of generals must agree on a common plan of action while some generals may be traitors sending conflicting messages.

## Features

- **Two Message Variants**: Oral messages (traitors can lie) and Signed messages (digital signatures prevent forgery)
- **Interactive Setup**: Configure number of generals, traitors, and initial orders
- **Visual Simulation**: Watch real-time message passing between generals
- **Consensus Verification**: Checks both Agreement (IC1) and Validity (IC2) conditions
- **Educational Logs**: Detailed step-by-step execution logs

## How to Run

Simply open `index.html` in any modern web browser. No server setup required.

## Usage

1. **Configure**:
   - Set number of generals (3-10)
   - Set number of traitors
   - Choose message type (Oral/Signed)
   - Select commander's initial order

2. **Run Simulation**:
   - Click "Setup Simulation" to initialize
   - Click "Run Simulation" to start
   - Watch messages propagate and consensus form

3. **Analyze Results**:
   - Check if consensus was achieved
   - Review detailed execution logs
   - Understand why consensus succeeded or failed

## Key Concepts Demonstrated

- **Oral Messages**: Requires n > 3m generals to handle m traitors
- **Signed Messages**: Allows consensus with any number of traitors
- **Byzantine Fault Tolerance**: Systems reaching agreement despite malicious components
- **Interactive Consistency**: All loyal nodes agreeing on the same value

## Technical Implementation

Pure HTML/CSS/JavaScript - no external dependencies. Runs entirely client-side in the browser.
