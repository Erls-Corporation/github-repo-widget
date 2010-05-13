# GitHub Repo Widget

For use on blogs, other websites, etc. This widget shows info for any public
repo on GitHub in the same style as seen on individual GitHub user pages.

It uses the GitHub JSON API to retrieve its data, so the API use policies and
rate limits apply.

## Code
    <style scoped="scoped">
    .gh_widget { width:428px;padding:5px;text-align:center;color:#888;
      font-size:12px;font-family:Helvetica,Arial,sans-serif;border-radius:4px;
      -moz-border-radius:4px;-webkit-border-radius:4px;border:1px solid #ddd }
    </style>
    <div id="gh_rails_rails" class="gh_widget">&hellip;</div>
    <script src="widget.js"></script>
    <script>GHWidget.init("gh_rails_rails", "rails/rails");</script>
