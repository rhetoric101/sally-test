# sally-test Does var <var>tag</var> work in Markdown?

<table>
  <thead>
    <tr>
      <th>
        CSP and browser agent
      </th>

      <th>
        Requirements
      </th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td>
        Application or platform
      </td>

      <td>
        Your app or platform where your site is hosted must meet browser's standard [compatibility requirements](/docs/browser/new-relic-browser/getting-started/compatibility-requirements-new-relic-browser). **Exception:** CSP restrictions prevent you from linking an APM app for browser monitoring.
      </td>
    </tr>

    <tr>
      <td>
        Subscription
      </td>

      <td>
        You must have a [**Pro+SPA** Browser subscription](https://newrelic.com/browser-monitoring/pricing) for your app.
      </td>
    </tr>

    <tr>
      <td>
        Host location for domains
      </td>

      <td>
        The `.js` file for the agent must be hosted on a highly available or replicated location, such as a CDN or distributed network. This helps ensure performance is not affected.

        * If you see error messages, add our browser monitoring domains to your [CSP whitelist](#csp-exception).
        * If you want to use the browser agent to [monitor Salesforce Lightning pages](/docs/csp-v2-monitor-salesforce-lightning-pages), follow the [Salesforce procedures](https://help.salesforce.com/articleView?id=csp_trusted_sites.htm&type=5) to add our  domains to your CSP whitelist.

        By hosting the agent, you are responsible for any performance impact on the location where the agent is hosted.
      </td>
    </tr>

    <tr>
      <td>
        Browser agent version
      </td>

      <td>
        Your selected app must use the [latest agent version](/docs/release-notes/new-relic-browser-release-notes/browser-agent-release-notes).
      </td>
    </tr>
  </tbody>
</table>
