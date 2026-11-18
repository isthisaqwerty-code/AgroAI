# AgroAI — Intelligent Agriculture

An independent AgriTech research project built in Uzbekistan. The long-term product vision combines **YOLO11-based plant health intelligence** and **Chronos-2-based soil moisture and air humidity forecasting** in one accessible application.

## Website
Public landing page and honest interactive UI preview: https://isthisaqwerty-code.github.io/AgroAI/

## Status
**Research / prototype stage.** The website is not a live ML inference service. Users can preview a local plant image and interact with clearly illustrative forecast curves. Actual trained-model inference remains an integration milestone.

## Technical approach
- **Computer vision:** YOLO11 experiments for plant disease / crop-stress detection, including dataset auditing and model improvement.
- **Time series:** Chronos-2 experiments using 8,760 hourly data records, with soil moisture and air humidity targets and a research forecasting horizon of 6 hours.
- **Product goal:** A unified decision-support experience designed for farms in Uzbekistan, with longer-term potential for livestock monitoring.

## Evidence and limitations
The early internal CV result (~78%) is *project-reported and preliminary*. Metric definition, independently reproducible test protocol, model weights, field validation, and source training notebooks are not yet published in this repository. The website does **not** claim certified accuracy, validated agronomic decisions, or production readiness.

## Next milestones
1. Publish reproducible experiment configurations, evaluation methodology, and model cards.
2. Connect hosted YOLO11 and forecasting inference endpoints securely.
3. Test on real farm imagery and sensor readings and gather farmer feedback.

## Development
The public website is a single static `index.html` file (HTML/CSS/vanilla JavaScript). Open it directly in a browser, or publish via the included GitHub Pages workflow.

## Founder
Independent founder / AI developer, Uzbekistan.
