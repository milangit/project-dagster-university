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


příště:
https://courses.dagster.io/courses/take/dagster-essentials/multimedia/48098606-loading-data-into-a-database
