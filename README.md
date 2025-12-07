# Maya 819-Day Calendar Calculator

A web-based calculator that determines your position within the ancient Maya 819-day astronomical cycle.

## Features

- **Current 819-Day Station**: Find which station you're in, when it started, and when it ends
- **45-Year Super Cycle**: Track progress through the complete 20-station super cycle (16,380 days / ~45 years)
- **Progress Visualization**: Visual progress bars for both the current station and super cycle
- **Planetary Synodic Periods**: Display how Mercury, Venus, Mars, Jupiter, and Saturn cycles align with the 819-day system
- **Date Selection**: Analyze any date to find its position in the cycle

## How It Works

The calculator uses the GMT correlation (584283) as the reference point, starting from the Maya epoch (~3114 BCE). The 819-day cycle is believed to have been used by the Maya to track planetary movements, with 20 stations completing one full cycle where all five visible planets realign.

## Usage

Simply open `maya-calendar-calculator.html` in a web browser. Select a date to see:
- Days into the current 819-day station
- Current station number (1-20)
- Years into the ~45-year super cycle
- Estimated completion dates

## Technologies

- React 18
- Tailwind CSS
- Babel (for JSX transformation)
