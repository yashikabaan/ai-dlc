# Estimation and Tracking

Last Updated: `<YYYY-MM-DD>`

## Purpose
Track planning quality and delivery reliability with lightweight signals.

## What to Track
- Estimate: initial effort estimate `<unit: points/hours/t-shirt>`
- Actual: actual effort at completion
- Variance: `actual - estimate`
- Delay: planned date vs actual completion date
- Risk Pattern: recurring causes of slippage/quality issues

## Practical Workflow
1. Add estimate during refinement/planning.
2. Record actual on completion.
3. Mark variance category: low/medium/high.
4. Tag primary cause when variance is high.
5. Review trends weekly.

## Variance Cause Tags (Example)
- Unknown scope
- Hidden dependency
- Rework from requirement change
- Quality defect fix
- Environment/tooling issue

## Lightweight Metrics
- Predictability: `% stories finished within planned sprint`
- Estimation Accuracy: `% items within accepted variance band`
- Carry-over Rate: `% planned work moved to next sprint`
- Risk Concentration: `top recurring cause over last <n> cycles`

## Future Prediction Support
- Use recent variance and carry-over trends to adjust:
  - sprint commitment level
  - risk buffers
  - decomposition quality
- Humans decide final planning commitments.
