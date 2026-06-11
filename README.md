# Chronis-Prototype
Chronis is a behavioral insight tool that transforms daily activity data into clear, useful insights. Instead of just showing numbers, it tells you what's changing, how confident you can be in that observation, and what might be causing it. Every insight comes with evidence, and when data is missing, we're upfront about it.


Chronis - Behavioral Insight Engine
What is Chronis?
Chronis is a behavioral analytics prototype that helps users understand their daily patterns across sleep, focus, mood, and activity. Instead of showing raw data and expecting users to figure it out, Chronis identifies meaningful patterns, explains them in plain language, and provides confidence scores so users know how much to trust each insight.

Key Features
Dashboard
View your key metrics at a glance. Four cards show sleep quality, focus score, mood average, and activity level with weekly comparisons. Interactive charts display trends over time. Confidence rings show data reliability for each metric.

Insight Explorer
Browse through all detected patterns and anomalies. Each insight includes a confidence score, supporting evidence with specific numbers, and a recommendation when applicable. Click any insight to see full details including date of detection and uncertainty explanations.

Narrative Timeline
See your behavioral journey presented as a story. Events like "sleep streak" or "focus dip" appear in chronological order with visual indicators for positive changes, anomalies, and recovery periods. This helps users understand cause and effect rather than just isolated data points.

Pattern Analysis
Discover how your behaviors connect. Correlation matrix shows relationships between different metrics like sleep and focus or exercise and mood. Time-of-day charts reveal when you perform best. Weekly rhythm analysis shows which days are strongest. Goal tracking shows progress toward personal targets.

Settings
Manage profile information, connected data sources, and notification preferences.

Confidence Scoring System
Every insight and data point includes a confidence score from 0 to 100 percent. This score reflects how reliable the underlying data is.

High confidence (80-100 percent) means sufficient data exists and patterns are clear. You can act on these insights.

Medium confidence (60-79 percent) means patterns are visible but some data is missing. Consider these insights but verify with your own experience.

Low confidence (below 60 percent) means limited data or weak patterns. Wait for more information before making changes.

When confidence is low, Chronis explains why. Common reasons include missing days of data, insufficient history, or weak statistical significance.

Evidence Backing
Every insight includes specific evidence so you know exactly what triggered it.

For example, an insight about sleep disruption shows:

The exact date of the disruption

The measured value versus your average

The percentage difference

The confidence score

Related metrics that might explain the change

No vague statements. No black box recommendations.

Uncertainty Handling
Chronis does not pretend to know things it does not know. When data is missing, confidence scores drop and explanations appear. When a pattern is too weak to report, Chronis stays silent rather than making a false claim.

This is built into the system by design. Premature insights are treated as failures.

Technical Implementation
Frontend: Next.js with Tailwind CSS
Charts: Chart.js for data visualization
Animations: CSS keyframes for subtle transitions
State Management: React hooks
Data: Synthetic mock data matching common wearable API formats

The prototype runs entirely on mock data. This allows full demonstration of features without requiring backend infrastructure or external API integrations. The data layer is abstracted, so replacing mock data with real API calls would require minimal changes.

Responsive Design
Chronis works on desktop, tablet, and mobile devices.

Desktop: Full sidebar navigation with 4-column grid layout

Tablet: Collapsible sidebar with 2-column grid

Mobile: Hidden sidebar with toggle button, single column stack

All charts resize automatically based on screen size.


