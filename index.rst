.. _docs-home-page:

**********
Welcome
**********

.. image:: _images/get-started/o11y-user-doc-hero-banner-v2.svg
   :alt: Welcome
   :width: 97.3%
   :target: https://docs.splunk.com/Observability/get-started/o11y.html#nav-Get-started


.. get your data in section

.. role:: icon-cloud-upload
.. rst-class:: newparawithicon

:icon-cloud-upload:`.` :strong:`Get your data in`
The first step toward observability is getting relevant data into Observability Cloud. View :ref:`all supported integrations <supported-data-sources>`.

.. gdi cards

.. rst-class:: newcard

:strong:`Get data in`
Learn how to get data in from each layer in your stack :ref:`get-started-get-data-in`


.. rst-class:: newcard

:strong:`Cloud providers`
Integrate to collect service metrics and logs :ref:`get-started-connect`


.. rst-class:: newcard

:strong:`Servers and clusters`
Install the Splunk Distribution of OpenTelemetry Collector to collect metrics and logs :ref:`get-started-compute`


.. rst-class:: newcard

:strong:`Back-end apps and services`
Instrument to collect traces and logs :ref:`get-started-application`


.. rst-class:: newcard

:strong:`Front-end app user experiences`
Instrument to collect user sessions :ref:`rum-gdi`


.. rst-class:: newcard

:strong:`Serverless functions`
Instrument to collect traces and logs :ref:`instrument-serverless-functions`


.. explore and monitor your env section

.. role:: icon-display
.. rst-class:: newparawithicon

:icon-display:`.` :strong:`Explore and monitor your environment`
After you have your data coming into Observability Cloud, it’s time to do some exploring.

.. explore and monitor cards

.. rst-class:: newcard

:strong:`Infrastructure Monitoring`
Monitor server and cluster metrics :ref:`wcidw-imm`

.. rst-class:: newcard

:strong:`Application Performance Monitoring`
Monitor back-end app and service traces :ref:`wcidw-apm`


.. rst-class:: newcard

:strong:`Real User Monitoring`
Monitor data about front-end app user experiences :ref:`wcidw-rum`


.. rst-class:: newcard

:strong:`Log Observer`
Query logs to identify root causes :ref:`LogObserverFeatures`


.. rst-class:: newcard

:strong:`Synthetic Monitoring`
Proactively monitor the performance of web resources :ref:`welcome-synthmon`


.. rst-class:: newcard

:strong:`All products`
Learn more about all Observability Cloud products :ref:`welcome`


.. set up alerts section

.. role:: icon-wrench
.. rst-class:: newparawithicon

:icon-wrench:`.` :strong:`Set up alerts and customize your account`
Prepare for issues that might arise by setting up alerts, custom dashboards, and other advanced features.

.. alerts and customize cards

.. rst-class:: newcard

:strong:`Detectors and alerts`
Receive alerts about conditions you care about :ref:`create-detectors`


.. rst-class:: newcard

:strong:`Dashboards and charts`
Get actionable insights about the systems you monitor :ref:`dashboards`


.. rst-class:: newcard

:strong:`Span tags`
Use span tags to add useful metadata to traces :ref:`apm-add-context-trace-span`


.. rst-class:: newcard

:strong:`Logs pipeline`
Add value to your raw logs by customizing your pipeline :ref:`logs-pipeline`


.. rst-class:: newcard

:strong:`Related Content`
Enable users to seamlessly move across product views :ref:`get-started-relatedcontent`


.. rst-class:: newcard

:strong:`Global Data Links`
Provide convenient access to relevant resources :ref:`link-metadata-to-content`


.. admin section

.. role:: icon-cogs
.. rst-class:: newparawithicon

:icon-cogs:`.` :strong:`Administer your account`
As an Observability Cloud administrator, use these tools to give your users a secure and relevant user experience.

.. admin cards

.. rst-class:: newcard

:strong:`Get started`
Learn how to set up and administer your organization :ref:`admin-admin`


.. rst-class:: newcard

:strong:`Access tokens`
Authenticate and track API use :ref:`admin-org-tokens`


.. rst-class:: newcard

:strong:`Users`
Invite users and set access levels :ref:`admin-manage-users`


.. rst-class:: newcard

:strong:`Teams`
Create teams to help coordinate teamwork :ref:`admin-manage-teams`


.. rst-class:: newcard

:strong:`Single sign-on`
Set up an integration to an SSO provider :ref:`sso-label`


.. rst-class:: newcard

:strong:`Subscription Usage`
Monitor subscription usage for Infrastructure Monitoring :ref:`monitor-imm-billing-usage`


.. popular integrations section

.. role:: icon-cloud-upload
.. rst-class:: newparawithicon

:icon-cloud-upload:`.` :strong:`Popular integrations`
Access documentation for some of the most popular integrations used to get data into Observability Cloud.


.. gdi cards

.. rst-class:: newcard

:strong:`Linux`
Collect metrics and logs :ref:`get-started-linux`


.. rst-class:: newcard

:strong:`Kubernetes`
Collect metrics and logs :ref:`get-started-k8s`


.. rst-class:: newcard

:strong:`Windows`
Collect metrics and logs :ref:`get-started-windows`


.. rst-class:: newcard

:strong:`Amazon Web Services`
Collect metrics and logs :ref:`get-started-aws`


.. rst-class:: newcard

:strong:`Azure`
Collect metrics :ref:`get-started-azure`


.. rst-class:: newcard

:strong:`Browser`
Collect user sessions :ref:`browser-rum-gdi`


.. rst-class:: newcard

:strong:`.NET`
Collect traces :ref:`get-started-dotnet`


.. rst-class:: newcard

:strong:`Java`
Collect traces :ref:`get-started-java`


.. rst-class:: newcard

:strong:`Ruby`
Collect traces :ref:`get-started-ruby`


.. rst-class:: newcard

:strong:`Node.js`
Collect traces :ref:`get-started-nodejs`


.. rst-class:: newcard

:strong:`PHP`
Collect traces :ref:`get-started-php`


.. rst-class:: newcard

:strong:`All supported integrations`
View a list of all supported integrations :ref:`supported-data-sources`


.. ----- This comment separates the landing page from the TOC -----

.. toctree::
   :caption: GET STARTED
   :maxdepth:   2

   get-started/welcome

.. toctree::
   :maxdepth:   3

   Get started <get-started/o11y>

.. toctree::
   :maxdepth:   3

   Use case: Monitor infrastructure and apps using the Collector <get-started/use-case-collector>

.. toctree::
   :maxdepth:   3

   Use case: Troubleshoot an issue from the browser to the backend <get-started/use-case>

.. toctree::
   :maxdepth:   3

   Support <get-started/support>

.. toctree::
   :caption: DATA MANAGEMENT
   :maxdepth:   3

   gdi/get-data-in/get-data-in

.. toctree::
   :maxdepth:   3

   gdi/get-data-in/integrations

.. toctree::
   :maxdepth:   3

   gdi/get-data-in/connect/connect

.. toctree::
   :maxdepth:   3

   gdi/get-data-in/compute/compute

.. toctree::
   :maxdepth:   3

   Instrument back-end services and applications <gdi/get-data-in/application/application>


.. toctree::
   :maxdepth:   3

   Instrument serverless functions <gdi/get-data-in/serverless/instrument-serverless-functions>

.. toctree::
   :maxdepth:  3

   Instrument front-end applications <gdi/get-data-in/rum/rum-instrumentation>

.. toctree::
   :maxdepth:   3

   gdi/index

.. toctree::
   :maxdepth: 3

   Splunk Distribution of OpenTelemetry Collector <gdi/opentelemetry/opentelemetry>

.. toctree::
   :maxdepth:   3

   Collector commands reference <gdi/agent-commands/otel-commands>

.. toctree::
   :maxdepth: 3

   gdi/other-ingestion-methods/other-data-ingestion-methods

.. toctree::
   :maxdepth: 3

   SignalFx Smart Agent (Deprecated) <gdi/smart-agent/smart-agent-intro>

.. toctree::
   :caption: DASHBOARDS AND CHARTS
   :maxdepth:   3

   Dashboards <data-visualization/dashboards/dashboards>

.. toctree::
   :maxdepth:   3

   Charts <data-visualization/charts/charts>

.. toctree::
   :maxdepth:   3

   Navigate with data links <data-visualization/navigate-with-data-links>   

.. toctree::
   :maxdepth:   3

   Override default time range <data-visualization/use-time-range-selector>   

.. toctree::
   :maxdepth:   3

   Read and write permissions <data-visualization/permissions>

.. toctree::
   :maxdepth:   3

   Related Content <data-visualization/relatedcontent>

.. toctree::
   :maxdepth:   3

   Enable Related Content <data-visualization/enablerelatedcontent>

.. toctree::
   :caption: ALERTS AND DETECTORS
   :maxdepth:   3

   Introduction to alerts and detectors <alerts-detectors-notifications/alerts-detectors-notifications>

.. toctree::
   :maxdepth:   3

   Alerts and detectors use case library <alerts-detectors-notifications/use-cases-detectors-alerts/use-cases-intro>

.. toctree::
   :maxdepth:   3

   AutoDetect in Splunk Observability Cloud <alerts-detectors-notifications/autodetect>

.. toctree::
   :maxdepth:   3

   List of available AutoDetect detectors <alerts-detectors-notifications/autodetect-list>

.. toctree::
   :maxdepth:   3

   Create detectors to trigger alerts <alerts-detectors-notifications/create-detectors-for-alerts>

.. toctree::
   :maxdepth:   3

   alerts-detectors-notifications/detector-manage-permissions

.. toctree::
   :maxdepth:   3

   Link detectors to charts <alerts-detectors-notifications/link-detectors-to-charts>

.. toctree::
   :maxdepth:   3

   Manage notification subscribers <alerts-detectors-notifications/manage-notifications>

.. toctree::
   :maxdepth:   3

   Detector options <alerts-detectors-notifications/detector-options>

.. toctree::
   :maxdepth:   3

   Preview detector alerts <alerts-detectors-notifications/preview-detector-alerts>

.. toctree::
   :maxdepth:   3

   View alerts <alerts-detectors-notifications/view-alerts>

.. toctree::
   :maxdepth:   3

   View detectors <alerts-detectors-notifications/view-detectors>

.. toctree::
   :maxdepth:  3

   Built-in alert conditions <alerts-detectors-notifications/alert-condition-reference/index>

.. toctree::
   :maxdepth:   3

   Mute alert notifications <alerts-detectors-notifications/mute-notifications>

.. toctree::
   :maxdepth:   3

   Auto-clearing alerts <alerts-detectors-notifications/auto-clearing-alerts>

.. toctree::
   :maxdepth:   3

   Troubleshoot detectors <alerts-detectors-notifications/troubleshoot-detectors>

.. toctree::
   :caption: APM
   :maxdepth:   3

   apm/intro-to-apm

.. toctree::
   :maxdepth:   3

   apm/set-up-apm/apm

.. toctree::
   :maxdepth:   3

   Use cases: Troubleshoot errors and monitor application performance <apm/apm-use-cases/apm-use-cases-intro>

.. toctree::
   :maxdepth:   3

   apm/key-concepts

.. toctree::
   :maxdepth:   3

   apm/apm-spans-traces/traces-spans

.. toctree::
   :maxdepth:   3

   Analyze services with span tags and MetricSets <apm/span-tags/span-tags>

.. toctree::
   :maxdepth:   3

   apm/workflows/workflows

.. toctree::
   :maxdepth:   3

   apm/apm-alert-visualize/alert-visualize

.. toctree::
   :maxdepth:   3

   AlwaysOn Profiling <apm/profiling/intro-profiling>

.. toctree::
   :maxdepth:   3

   apm/db-query-perf/db-query-performance

.. toctree::
   :maxdepth:   3

   apm/apm-data-links/data-links-landing

.. toctree::
   :caption: INFRASTRUCTURE
   :maxdepth:   3

   Introduction <infrastructure/intro-to-infrastructure>

.. toctree::
   :maxdepth:   2

   Quick start tutorial <infrastructure/quickstart-imm>

.. toctree::
   :maxdepth:   3

   infrastructure/infrastructure

.. toctree::
   :maxdepth:   3

   Key concepts <infrastructure/terms-concepts>

.. toctree::
   :maxdepth:   3

   Monitor services and hosts <infrastructure/monitor/monitor-services-hosts>

.. toctree::
   :maxdepth:   3

   Use navigators <infrastructure/use-navigators>


.. toctree::
   :maxdepth:   3

   Virtual metrics <infrastructure/virtual-metrics>

.. toctree::
   :maxdepth:   3

   infrastructure/analytics/signalflow-analytics-intro

.. toctree::
   :maxdepth:   3

   Resolution and data retention <infrastructure/retention>

.. toctree::
   :maxdepth:   3

   Resolution and data retention (DPM) <infrastructure/dpm-retention>

.. toctree::
   :maxdepth:   3

   System limits <infrastructure/sys-limits>

.. toctree::
   :caption: LOG OBSERVER
   :maxdepth:   3

   logs/intro-logconnect

.. toctree::
   :maxdepth:   3

   logs/scp

.. toctree::
   :maxdepth:   3

   logs/set-up-logconnect 

.. toctree::
   :maxdepth:   3

   logs/LOconnect-troubleshoot

.. toctree::
   :maxdepth:   3

   logs/get-started-logs

.. toctree::
   :maxdepth:   3

   logs/logs

.. toctree::
   :maxdepth:   3

   logs/timeline

.. toctree::
   :maxdepth:   3

   logs/live-tail

.. toctree::
   :maxdepth:   3

   logs/queries

.. toctree::
   :maxdepth:   3

   logs/raw-logs-display

.. toctree::
   :maxdepth:   3

   logs/keyword

.. toctree::
   :maxdepth:   3

   logs/filter-logs-by-field

.. toctree::
   :maxdepth:   3

   logs/alias

.. toctree::
   :maxdepth:   3

   logs/individual-log

.. toctree::
   :maxdepth:   3

   logs/message-field

.. toctree::
   :maxdepth:   3

   logs/aggregations

.. toctree::
   :maxdepth:   3

   logs/search-time-rules

.. toctree::
   :maxdepth:   3

   logs/save-share

.. toctree::
   :maxdepth:   3

   logs/logviews

.. toctree::
   :maxdepth:   3

   logs/pipeline

.. toctree::
   :maxdepth:   3

   logs/processors 

.. toctree::
   :maxdepth:   3

   logs/metricization

.. toctree::
   :maxdepth:   3

   logs/infinite

.. toctree::
   :maxdepth:   3

   logs/timestamp

.. toctree::
   :maxdepth:   3

   logs/limits

.. toctree::
   :caption: RUM
   :maxdepth:   3

   rum/intro-to-rum

.. toctree::
   :maxdepth:   3

   Set up Splunk RUM <rum/set-up-rum>

.. toctree::
   :maxdepth:   3

   rum/rum-use-case-library/use-case-landingpage

.. toctree::
   :maxdepth:   3

   rum/data-collected

.. toctree::
   :maxdepth:   3

   rum/rum-terminology-concepts


.. toctree::
   :maxdepth:   3

   rum/RUM-custom-events

.. toctree::
   :maxdepth:   3

   rum/error-aggregates

.. toctree::
   :maxdepth:   3

   rum/rum-tag-search

.. toctree::
   :maxdepth:   3

   rum/rum-rules

.. toctree::
   :maxdepth:   3

   rum/rum-alerts

.. toctree::
   :maxdepth:   3

   rum/rum-dashboards/rum-dashboards

.. toctree::
   :maxdepth:   3

   rum/RUM-metrics


.. toctree::
   :maxdepth:   3

   rum/sample-app
.. toctree:: 
   :maxdepth:    3

   rum/rum-limits

.. toctree::
   :maxdepth:   3

   rum/rum-third-party-software

.. toctree::
   :caption: SYNTHETICS
   :maxdepth:   3

   synthetics/intro-synthetics

.. toctree::
   :maxdepth:   3

   synthetics/set-up-synthetics/set-up-synthetics

.. toctree::
   :maxdepth:   3

   synthetics/key-concepts

.. toctree::
   :maxdepth:   3 
  
   synthetics/synth-use-cases/synth-landing

.. toctree::
   :maxdepth:   3

   synthetics/browser-test/browser-test

.. toctree::
   :maxdepth:   3

   synthetics/uptime-test/uptime-test

.. toctree::
   :maxdepth:   3

   synthetics/api-test/api-test

.. toctree::
   :maxdepth:   3

   synthetics/test-config/test-config

.. toctree::
   :caption: UNDERSTAND YOUR DATA
   :maxdepth:   3

   Metrics, data points, and metric time series <metrics-and-metadata/metrics>

.. toctree::
   :maxdepth:   3

   metrics-and-metadata/metric-types

.. toctree::
   :maxdepth:   3

   Dimensions, custom properties, and tags <metrics-and-metadata/metrics-dimensions-mts>

.. toctree::
   :maxdepth:   3

   metrics-and-metadata/metric-names

.. toctree::
   :maxdepth:   3

   Add context to metrics using events <metrics-and-metadata/view-data-events>

.. toctree::
   :maxdepth:   3

   metrics-and-metadata/metrics-finder-metadata-catalog

.. toctree::
   :caption: MOBILE
   :maxdepth:   3

   mobile/intro-to-mobile

.. toctree::
   :maxdepth:   3

   Download the app <mobile/download-mobile>

.. toctree::
   :maxdepth:   3

   View dashboards and alerts <mobile/use-mobile>

.. toctree::
   :caption: ADMINISTER OBSERVABILITY CLOUD
   :maxdepth:   3

   admin/admin

.. toctree::
   :maxdepth:   3

   Use case: Maintain a secure organization with many teams and users <admin/use-case-org-security>

.. toctree::
   :hidden:
   :maxdepth:   3

   admin/SSO/sso

.. toctree::
   :maxdepth:   3

   Create and manage authentication tokens <admin/authentication-tokens/tokens>

.. toctree::
   :hidden:
   :maxdepth:   3

   admin/allow-services

.. toctree::
   :maxdepth:   3

   Create and manage users <admin/users/manage-users>

.. toctree::
   :maxdepth:   3

   Create and manage teams <admin/teams/manage-teams>


.. toctree::
   :hidden:
   :maxdepth:   3

   Send alert notifications to third-party services <admin/notif-services/admin-notifs-index>

.. toctree::
   :hidden:
   :maxdepth:   3

   Link metadata to related resources using global data links <admin/link-metadata-to-content>

.. toctree::
   :maxdepth:   3

   View organization metrics <admin/org-metrics>
.. toctree::
   :hidden:
   :maxdepth:   3

   admin/apm-billing-usage/apm-billing-usage-index

.. toctree::
   :hidden:
   :maxdepth:   3

   admin/imm-billing-usage/monitor-imm-billing-usage

.. toctree::
   :hidden:
   :maxdepth:   3

   admin/imm-billing-usage/dpm-usage



.. toctree::
   :caption: SETTINGS AND REFERENCE
   :maxdepth:   3

   Password and contact information <references/personal-info>

.. toctree::
   :maxdepth:   3

   Organizations <references/organizations>

.. toctree::
   :maxdepth:   3

   Teams <references/teams>

.. toctree::
   :maxdepth:   3

   Time zone and color accessibility settings <references/app-preferences>

.. toctree::
   :maxdepth:   3

   API access token <references/api-access-token>

.. toctree::
   :maxdepth:   3

   Supported browsers <references/supported-browsers>

.. toctree::
   :maxdepth:   3

   Third-party software credits <references/third-party-credits>

.. toctree::
   :maxdepth:   3

   Data retention <references/data-retention>

.. toctree::
   :maxdepth:   3

   Glossary <references/glossary>
