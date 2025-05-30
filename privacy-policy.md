<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Privacy Policy - DSU SOAPBOX Extension</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            line-height: 1.6;
            margin: 0 auto;
            max-width: 800px;
            padding: 20px;
            color: #333;
        }
        h1 {
            font-size: 2em;
            color: #2c3e50;
            border-bottom: 2px solid #ecf0f1;
            padding-bottom: 0.3em;
            margin-top: 0;
        }
        h2 {
            font-size: 1.5em;
            color: #34495e;
            margin-top: 1.5em;
            margin-bottom: 0.5em;
            border-bottom: 1px solid #ecf0f1;
            padding-bottom: 0.2em;
        }
        p {
            margin-bottom: 1em;
        }
        ul {
            margin-bottom: 1em;
            padding-left: 20px;
        }
        li {
            margin-bottom: 0.5em;
        }
        strong {
            font-weight: 600;
        }
        code {
            background-color: #f4f7f6;
            padding: 0.2em 0.4em;
            border-radius: 3px;
            font-family: 'SFMono-Regular', Consolas, 'Liberation Mono', Menlo, Courier, monospace;
            font-size: 0.9em;
        }
        .meta-info {
            font-size: 0.9em;
            color: #7f8c8d;
            margin-bottom: 2em;
        }
        .contact-info a {
            color: #3498db;
            text-decoration: none;
        }
        .contact-info a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <h1>Privacy Policy for DSU SOAPBOX Extension</h1>

    <p class="meta-info">
        <strong>Last Updated:</strong> May 11, 2025
    </p>

    <p>Thank you for using DSU SOAPBOX (the "Extension"), programmed by Shannon Higgins <a href="mailto:ShannonHiggins@outlook.com">ShannonHiggins@outlook.com</a>. This Privacy Policy explains how the Extension collects, uses, and protects your information.</p>

    <p>By installing and using the Extension, you agree to the terms of this Privacy Policy.</p>

    <h2>1. Information We Collect (and Don't Collect)</h2>

    <p>The DSU SOAPBOX Extension is designed to help you organize and track lists of names or items within user-defined groups.</p>

    <ul>
        <li><strong>User-Generated Data Stored Locally:</strong> The Extension allows you to create and store data directly within your Chrome browser. This data includes:
            <ul>
                <li>Group names</li>
                <li>Names or items within those groups</li>
                <li>Checkbox states (checked/unchecked) for each name/item</li>
                <li>Color assignments for name/item swatches</li>
            </ul>
        </li>
        <li><strong>No Personal Information Collected Automatically:</strong> The Extension <strong>does not</strong> automatically collect, store, or transmit any personally identifiable information (PII) about you, such as your name (other than what you enter as group/item names), email address, IP address, or browsing history.</li>
        <li><strong>No Server-Side Storage by the Extension:</strong> All the data you create within the Extension is stored locally on your computer using Chrome's Storage API (<code>chrome.storage.sync</code>).</li>
        <li><strong>No Third-Party Tracking:</strong> The Extension does not include any third-party trackers, analytics services (unless explicitly added by you via Google Analytics ID in the store listing, which tracks store page views, not extension usage), or advertising.</li>
    </ul>

    <h2>2. How We Use Your Information</h2>

    <ul>
        <li><strong>To Provide Extension Functionality:</strong> The data you create (groups, names, checkbox states, colors) is used solely to provide the features of the Extension, allowing you to organize, view, and manage your lists as intended.</li>
        <li><strong>Data Synchronization (via Chrome Sync):</strong> If you are signed into your Google Account in Chrome and have Chrome Sync enabled, the data stored by the Extension using <code>chrome.storage.sync</code> may be automatically synchronized by Google across your signed-in Chrome browsers. This synchronization is a feature of Google Chrome and is subject to Google's Privacy Policy. The DSU SOAPBOX Extension itself does not control or manage this synchronization process beyond utilizing the <code>chrome.storage.sync</code> API.</li>
    </ul>

    <h2>3. How Your Information Is Stored and Protected</h2>

    <ul>
        <li><strong>Local Storage:</strong> All data created within the Extension is stored locally in your Chrome browser's storage.</li>
        <li><strong>Security:</strong> While the Extension itself does not add extra layers of encryption to the data stored by <code>chrome.storage.sync</code> (as this is handled by the browser and Google's infrastructure for synced data), we recommend you follow standard security practices for your Google account and computer to protect your browser data.</li>
    </ul>

    <h2>4. Information Sharing and Disclosure</h2>

    <p>The DSU SOAPBOX Extension <strong>does not share, sell, rent, or trade your user-generated data with any third parties.</strong> All data you input into the extension remains within your browser's storage or, if Chrome Sync is enabled, within your Google account's synced data.</p>

    <p>The Extension does not transmit your data to any external servers controlled by the developer (Shannon Higgins DHCS) or any other third party.</p>

    <h2>5. Permissions Used by the Extension</h2>

    <p>The Extension requests the following permissions in Chrome, with justifications as follows:</p>

    <ul>
        <li><strong><code>storage</code></strong>: Required to save your created groups, names, checkbox states, and color assignments locally in your browser and to allow Chrome to sync this data if you have Chrome Sync enabled. This ensures your data persists across browser sessions.</li>
        <li><strong><code>activeTab</code></strong> and <strong><code>scripting</code></strong>: Required to inject the Extension's user interface panel (as an iframe) into the currently active webpage. This allows you to interact with your lists directly on the page you are viewing. <code>scripting</code> is used to manage the injection and communication with the UI panel, and <code>activeTab</code> helps ensure this functionality is applied to the intended page.</li>
    </ul>

    <h2>6. Children's Privacy</h2>

    <p>The Extension is not directed at individuals under the age of 13. We do not knowingly collect personal information from children under 13.</p>

    <h2>7. Changes to This Privacy Policy</h2>

    <p>We may update this Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy within the Extension's Chrome Web Store listing. You are advised to review this Privacy Policy periodically for any changes. Changes to this Privacy Policy are effective when they are posted on this page.</p>

    <h2>8. Contact Us</h2>

    <p class="contact-info">If you have any questions about this Privacy Policy, please contact:<br>
    Shannon Higgins <a href="mailto:ShannonHiggins@outlook.com">ShannonHiggins@outlook.com</a>.</p>

</body>
</html>
