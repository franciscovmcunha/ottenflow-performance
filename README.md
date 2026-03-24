# OttenFlow Performance

Real-world validation of OttenFlow — from guest data to revenue.

This repository tracks experiments, results, and insights generated while validating OttenFlow in a live hotel environment.

---

## Purpose

The goal of this repository is to provide evidence of impact.

While the main OttenFlow repository focuses on system design and architecture, this repository answers a different question:

Does it actually generate revenue?

---

## What Is Being Tested

OttenFlow is built around a core operational loop:

data → action → conversation → conversion → revenue

This repository documents how that loop performs in real-world conditions.

---

## Experiment Types

1. Campaigns (Past Guests)

- Source: historical guest data  
- Action: outbound personalized messages  
- Goal: reactivation and direct bookings  

2. Concierge (New Bookings)

- Source: booking confirmation emails  
- Action: pre-arrival communication (e.g. transfers, upsells)  
- Goal: capture additional revenue before check-in  

---

## Repository Structure

experiments/
    campaign_YYYY_MM/
    concierge_YYYY_MM/

metrics/
    global_metrics.csv
    definitions.md

raw_logs/
    message_logs_snapshot.csv
    deals_snapshot.csv
    conversations_snapshot.csv

---

## Metrics Tracked

Each experiment tracks:

- Messages sent  
- Replies received  
- Interested guests  
- Bookings confirmed  
- Revenue generated  

Core KPIs:

- Reply Rate = replies / messages sent  
- Interest Rate = interested / messages sent  
- Conversion Rate = bookings / messages sent  

---

## Example Flow

1. Guests are selected or ingested (campaign or booking)
2. A message is generated and sent manually
3. Guest replies are logged
4. Conversations are classified (INTERESTED, BOOKED, etc.)
5. Revenue is tracked

---

## Why This Matters

Most hospitality tools focus on:

- dashboards  
- reporting  
- passive insights  

OttenFlow focuses on:

execution and measurable outcomes

This repository demonstrates that:

- Guest data can be turned into actions  
- Conversations can be structured  
- Revenue can be generated from operational signals  

---

## Key Insight

Even without full automation, a structured system combining:

- data  
- messaging  
- tracking  

is sufficient to create a measurable revenue pipeline.

---

## Related Repository

Core system and architecture:  
OttenFlow (main repository)

---

## Status

Ongoing validation in a real hotel environment.

Experiments are continuously added with:

- new datasets  
- refined messaging strategies  
- improved conversion approaches  

---

## Contact

info@ottenflow.com
