# pr-comments-monitor
IntelliJ Idea plugin to monitor all open GitHub Pull Requests in your project's repository and notifies you about new/unread comments.
https://plugins.jetbrains.com/plugin/31300-github-pr-comments-monitor

<p>
    Stay on top of every GitHub PR conversation without leaving your IDE.
    <b>GitHub PR Comments Monitor</b> continuously polls your repository for new and edited review comments
    across all open Pull Requests, delivers desktop notifications, and gives you a dedicated tool window
    to browse, preview, and navigate comments — all in one place.
</p>

<h3>Core Features</h3>
<ul>
    <li><b>Automatic polling</b> — Periodically fetches comments from all open PRs via the GitHub API using your IDE's GitHub account.</li>
    <li><b>Desktop notifications</b> — Balloon alerts for new and edited comments with quick actions: jump to file, view in tool window, or open on GitHub.</li>
    <li><b>Unread reminders</b> — Optional periodic reminders when you have unread comments and the tool window is not visible.</li>
    <li><b>Edit detection</b> — Edited comments are automatically marked as unread and flagged with an "(edited)" label so you never miss an update.</li>
    <li><b>Read / unread tracking</b> — Per-comment read state with a dynamic unread-count badge on the tool window icon.</li>
    <li><b>GitHub notification sync</b> — Optionally sync read state with GitHub's Notifications API (inbound-only or bidirectional).</li>
</ul>

<h3>Tool Window</h3>
<ul>
    <li><b>Tree view</b> — Comments organized by PR → file (with file-type icons) → individual comments and replies.</li>
    <li><b>Comment preview</b> — Rendered HTML preview pane with a resizable splitter.</li>
    <li><b>One-click navigation</b> — Click a comment to open the exact file and line in the editor; branch mismatch detection prompts you to check out the correct branch first.</li>
    <li><b>Configurable double-click</b> — Choose between opening the local file or opening the comment on GitHub.</li>
    <li><b>Toolbar controls</b> — Refresh, expand / collapse all, mark all as read, filter by author, toggle unread-only view, toggle preview pane, and quick access to settings.</li>
    <li><b>Per-PR muting</b> — Right-click any PR node to mute it; unmute anytime from the toolbar dropdown.</li>
</ul>

<h3>Highly Customizable via Settings</h3>
<p>Fine-tune the plugin to your workflow under <b>Settings → Tools → GitHub PR Comments Monitor</b>:</p>
<ul>
    <li><b>Polling interval</b> — From 1 to 60 minutes.</li>
    <li><b>PR author filter</b> — Show all PRs, only your own, or use a whitelist / blacklist of GitHub usernames.</li>
    <li><b>Comment author filter</b> — Whitelist or blacklist specific comment authors.</li>
    <li><b>Open PRs only</b> — Optionally hide closed / merged PRs.</li>
    <li><b>Double-click action</b> — Open file in editor or open on GitHub.</li>
    <li><b>Notification sync mode</b> — Disabled, inbound-only, or bidirectional sync with GitHub notifications.</li>
    <li><b>Unread reminders</b> — Enable or disable periodic reminder balloons.</li>
    <li><b>Storage limits</b> — Max open PRs to fetch, max stored comments, and retention period.</li>
</ul>

<h3>Requirements</h3>
<ul>
    <li>IntelliJ IDEA 2025.1 or later (Community or Ultimate).</li>
    <li>Bundled <b>GitHub</b> and <b>Git</b> plugins must be enabled.</li>
    <li>At least one GitHub account configured in <b>Settings → Version Control → GitHub</b>.</li>
</ul>

<h2>Versions:</h2>

<h3>1.0.0</h3>
<ul>
    <li><b>Automatic polling</b> — Continuously fetches comments from all open PRs via the GitHub API.</li>
    <li><b>Desktop notifications</b> — Balloon alerts for new and edited comments with quick actions: jump to file, view in tool window, or open on GitHub.</li>
    <li><b>Unread reminders</b> — Optional periodic reminders when unread comments are waiting.</li>
    <li><b>Edit detection</b> — Edited comments are marked unread and flagged "(edited)".</li>
    <li><b>Read / unread tracking</b> — Per-comment read state with a dynamic badge on the tool window icon.</li>
    <li><b>GitHub notification sync</b> — Sync read state with GitHub Notifications API (inbound or bidirectional).</li>
    <li><b>Tree view</b> — Comments organized by PR → file → individual comments and replies.</li>
    <li><b>HTML comment preview</b> — Rendered preview pane with resizable splitter.</li>
    <li><b>One-click code navigation</b> — Jump to the exact file and line; branch mismatch detection with checkout prompt.</li>
    <li><b>PR author filter</b> — Show all, only yours, or whitelist / blacklist specific authors.</li>
    <li><b>Comment author filter</b> — Whitelist or blacklist comment authors.</li>
    <li><b>Per-PR muting</b> — Mute noisy PRs from the context menu; unmute anytime.</li>
    <li><b>Configurable double-click</b> — Open file in editor or open on GitHub.</li>
    <li><b>Extensive settings</b> — Polling interval, storage limits, retention period, notification sync mode, and more.</li>
</ul>
