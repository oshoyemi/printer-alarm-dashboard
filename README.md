# 🖨️ Printer Alarm per 1000 Dashboard

All-DC Printer Alarm Dashboard tracking alarm counts and durations across 23 Distribution Centers.

## 🔗 Live Dashboard

**[View Dashboard →](https://oshoyemi.github.io/printer-alarm-dashboard/)**

## 📊 Features

- Daily alarm trend analysis
- Alarms by DC, printer type, and cell
- Hourly breakdown with shift impact analysis
- Interactive filters (DC, Site, Cell, Printer Type, Date Range)
- Walmart Week support
- Auto-refresh daily at 5:05 AM (BQ data refreshes at 5:00 AM)

## 🔄 Auto-Update Schedule

| Step | Time | Action |
|------|------|--------|
| 1 | 5:00 AM | Windows Task Scheduler runs `refresh_printer_alarm_dashboard.py` → queries BigQuery |
| 2 | 5:05 AM | Browser auto-reloads page with fresh data |

## 🐶 Built with Code Puppy
