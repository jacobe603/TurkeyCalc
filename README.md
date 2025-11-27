# Turkey Cooking Calculator

A single-file web app for calculating turkey cooking times with step-by-step guidance and timed reminders.

## Features

- **Weight-based cooking time calculation** - Supports 6-30 lbs in 0.25 lb increments
- **Fresh or frozen turkey options** - Automatically adjusts time for partially (+25%) or fully frozen (+50%) turkeys
- **Stuffed/unstuffed selection** - Accounts for longer cooking times when stuffed
- **Target finish time picker** - Set when you want to eat, get told when to start
- **Live countdown timer** - Tracks progress through cooking milestones
- **Browser notifications** - Get alerts even when the tab is in the background
- **Sound alerts** - Audio notification for each milestone
- **localStorage persistence** - Timer survives page refreshes
- **Print-friendly schedule** - Print your cooking timeline for reference
- **Calculation breakdown** - See the math behind the estimated cook time

## Cooking Data

Times are based on the official [Butterball Roasting Guide](https://www.butterball.com/how-to/cook-a-turkey/roast) for a conventional oven at 325F.

## Usage

1. Open `turkey-calc.html` in any modern browser
2. Set your turkey weight using the slider
3. Select fresh/frozen and stuffed/unstuffed options
4. Pick your target finish time (when you want to carve)
5. Click "Start Cooking Timer" when you put the turkey in the oven
6. Follow the milestone reminders throughout cooking

## Milestones Tracked

- Preheat oven reminder
- Turkey in oven
- Basting reminders (every 45 minutes)
- Cover with foil (at 2/3 cooking time)
- Temperature check (30 minutes before done)
- Turkey done (165F internal)
- Rest period (20 minutes)
- Ready to carve

## License

MIT
