# Daily Updates

This folder stores the generated daily OpenSRE update archives committed by the scheduled GitHub Actions workflow in `.github/workflows/daily-update.yml`.

Each run writes one markdown file per London calendar day using the filename format `YYYY-MM-DD.md`.

You can also run the workflow manually from the GitHub Actions tab with `workflow_dispatch`, optionally choosing a specific London date and whether the run should post to Slack. If you leave the date blank on a manual rerun, the workflow defaults to the previous London day so late-night reruns regenerate the intended report instead of the new calendar day.
