https://courses.dagster.io/courses/take/dagster-essentials/multimedia/48036632-defining-your-first-asset
https://dagster.io/docs/getting-started/installation
uvx create-dagster
dg scaffold project


cd /
cd ~
cd /home/milan/github/personal/project-dagster-university/dagster_university/dagster_essentials
cd /home/milan/github/personal/project-dagster-university

uv sync
source .venv/bin/activate

dg scaffold defs dagster.asset assets/trips.py
dg check defs
dg dev
http://127.0.0.1:3000/overview/activity/timeline?groupBy=automation


dg launch --assets taxi_trips_file


dg scaffold defs dagster.asset assets/metrics.py


dg scaffold defs dagster.resources resources.py
dg scaffold defs dagster.job jobs.py
dg scaffold defs dagster.schedule schedules.py


příště:
https://courses.dagster.io/courses/take/dagster-essentials/multimedia/48099851-what-s-a-code-location
