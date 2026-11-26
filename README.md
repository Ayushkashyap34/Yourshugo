# YourShugo

An AI guardian for ageing parents, and peace of mind for the children who look after them from another city.

> Personal assistance is not a luxury, it is a need.

## The problem

Technology changes faster than many people can keep up with. Elders overpay for orders and subscriptions they can't easily check, and their working children, often far away and managing loans on a single income, end up as the unpaid project manager of their parents' health and logistics.

## What this prototype shows

One page, two connected screens that share the same live data:

- **Senior app (Kamala's app):** large, simple UI. Say what you need (groceries, medicine, a doctor, a school) and YourShugo compares prices, finds coupons, or suggests nearby doctors. Urgent symptoms (e.g. chest pain) skip booking and point to emergency care.
- **Family dashboard (Ravi's dashboard):** status at a glance, a "Needs your OK" approval queue, activity log, savings tracker, and a way to send requests to the parent.
- **Everything is linked:** a request in the senior app appears in the family queue; approving it updates the senior's list; marking a tablet as taken updates the dashboard.

## Run it

It is a single static file with no build step.

1. Open `index.html` in a browser, or
2. Host it with GitHub Pages: Settings -> Pages -> Deploy from branch -> `main` / root.

## Limitations (it is a prototype)

- Prices, doctors and schools are **sample data**.
- Understanding of what the user types uses **simple keyword rules**, not a real AI model.
- State is in memory only and resets on refresh.
- YourShugo compares prices and tracks reminders. It does **not** give medical advice.

## Roadmap

- Real language understanding via an AI backend
- Real pharmacy, doctor and school data and booking partners
- Family-configurable approval rules
- Kids' privacy mode and a time-saving mode for young adults
- Safety review of symptom routing with medical advisors before any real use

## Status

Early-stage idea.

**##Off Campus code:-5MKEAX**
