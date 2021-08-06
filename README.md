# sally-test Does var <var>tag</var> work in Markdown?

<table>
  <thead>
    <tr>
      <th>Heading 1</th>
      <th>Headng 2</th>
    </tr>
  <tbody>
    <tr>
      <td>Column 1</td>
      <td>Column 2</td>
    </tr>
    <tr>
      <td>Column 1</td>
      <td>Column 2</td>
    </tr>
  </tbody>
 </table>
 

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
        <p>Your app or platform where your site is hosted must meet browser's standard  <a href="https://docs.newrelic.com/docs/browser/new-relic-browser/getting-started/compatibility-requirements-new-relic-browser">compatibility requirements</a>. **Exception:** CSP restrictions prevent you from linking an APM app for browser monitoring.</p>
      </td>
    </tr>

    <tr>
      <td>
        Subscription
      </td>

      <td>
        You must have a <a href="https://newrelic.com/browser-monitoring/pricing">Pro+SPA Browser subscription</a> for your app.
      </td>
    </tr>

    <tr>
      <td>
        Host location for domains
      </td>

      <td>
        <p>The `.js` file for the agent must be hosted on a highly available or replicated location, such as a CDN or distributed network. This helps ensure performance is not affected.</p>

        <ul>
          <li>If you see error messages, add our browser monitoring domains to your [CSP whitelist](#csp-exception)</li>
          <li> If you want to use the browser agent to <a href="https://docs.newrelic.com/docs/csp-v2-monitor-salesforce-lightning-pages">monitor Salesforce Lightning pages</a> follow the <a href="https://help.salesforce.com/articleView?id=csp_trusted_sites.htm&type=5:">Salesforce procedures</a> to add our domains to your CSP whitelist.</li>
        </ul>

        <p>By hosting the agent, you are responsible for any performance impact on the location where the agent is hosted.</p>
      </td>
    </tr>

    <tr>
      <td>
        Browser agent version
      </td>

      <td>
        Your selected app must use the <a href="https://docs.newrelic.com/docs/release-notes/new-relic-browser-release-notes/browser-agent-release-notes">latest agent version</a>.
      </td>
    </tr>
  </tbody>
</table>
