# covid19

Based off of data from JHU which is included as submodule repo in /bin dir: https://github.com/CSSEGISandData/COVID-19 

Initialize submodule:

```git submodule update --init --recursive```

Includes a monitor of sub directory: /csse_covid_19_data/csse_covid_19_daily_reports/

Run a git pull on the COVID-19 directory to update the data.

```git pull --recurse-submodules```

**Prereqs:**

Maps+ for Splunk: https://splunkbase.splunk.com/app/3124/

![Image of Dashboard](https://github.com/benwalthall/covid19/blob/master/static/CoronavirusDashboards.png?raw=true)