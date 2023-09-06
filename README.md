# iCal parsing tests

This is a Node.js script that fetches a remote iCal file, filters events, and prints events occurring from today to the next 4 weeks. It also handles recurring events based on the provided RRULE.

## Prerequisites

- Node.js installed on your machine.

## Installation

1. Clone the repository or download the code as a ZIP file.
2. Install the required dependencies using npm:

```bash
npm install axios node-ical moment
```

## Usage
Replace the url of the actual remote iCal file you want to fetch in the variable remoteICalUrl of the calendar-test.js file with and run the script using Node.js:

```bash
node calendar-test.js
```

The script will fetch the iCal file, filter and print events occurring from today to the next 4 weeks, including recurring events.

## Output
The script will display event details for each event that falls within the specified date range. For each event, the following information will be shown:

```
Title: The title of the event.
Description: The description of the event.
Start Date: The start date and time of the event.
End Date: The end date and time of the event.
Timezone: The timezone of the event (if available).
Duration: The duration of the event.

title: Birthday Party
Description: The description Birthday Party.
startDate: August 5th 2023, 2:00:00 pm
endDate: August 5th 2023, 6:00:00 pm
timezone: America/New_York
duration: 4 hours

title: Weekly Meeting
Description: The description of Weekly Meeting.
startDate: August 10th 2023, 10:00:00 am
endDate: August 10th 2023, 11:30:00 am
timezone: Europe/London
duration: 1 hour 30 minutes
```

## License
This project is licensed under the MIT License.

Feel free to use, modify, and distribute this code as needed.

## Acknowledgments
This script uses the following npm packages: axios, node-ical, and moment.
Special thanks to the authors and contributors of these libraries.






