# WattWise

WattWise is a web app that helps households understand where their electricity is being used and find realistic ways to reduce their monthly bill.

## The problem

Electricity bills can increase without it being clear which appliances are responsible. Many households do not have smart meters or appliance-level energy tracking, so it is difficult to know where to start.

## What WattWise does

Users can add appliances such as air conditioners, fans, refrigerators, lights, geysers, TVs, and washing machines. For each appliance, they can enter its wattage, quantity, and estimated hours of use per day.

WattWise will estimate:

* Monthly electricity consumption in units (kWh)
* Estimated monthly cost for each appliance
* The appliances using the most electricity
* Possible savings from reducing usage

## How the calculation works

Estimated monthly units:

`(Wattage × Quantity × Hours used per day × 30) ÷ 1000`

Estimated monthly cost:

`Monthly units × electricity rate per unit`

The results are estimates. Actual usage can vary based on appliance efficiency, settings, weather, and household habits.

## Planned features

* Add, edit, and remove appliances
* Appliance-wise monthly cost breakdown
* Biggest energy users dashboard
* Savings simulator for changing daily usage
* Electricity-rate setting
* Charts and visual summaries
* Save household data in the browser using local storage
* Mobile-friendly design

## Tech stack

* HTML
* CSS
* JavaScript
* Browser Local Storage

## Running the project locally

1. Download or clone this repository.
2. Open `index.html` in a web browser.

## Why I am building this

I am building WattWise after seeing a household electricity bill increase without a clear way to identify which appliances were contributing most. The goal is to create a simple tool that makes energy use easier to understand for ordinary households.

## Status

Currently in development.
