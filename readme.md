# Awesome Cloudflare [<img src="media/cf-logo.svg" width="250" align="right" alt="Cloudflare">](https://www.cloudflare.com)

> Curated list of awesome [Cloudflare](https://www.cloudflare.com) worker recipes, open-source projects, guides, blogs and other resources.

## Contents

- [Community](#community)
- [Blog](#blog)
- [DNS](#dns)
- [Developers](#developers)
- [Apps](#apps)
  - [Open Source](#open-source)
- [Workers](#workers)
  - [Reference](#reference)
  - [Tools](#tools)
  - [Recipes](#recipes)
- [Other](#other)

## Community

- [Forum](https://community.cloudflare.com)
- [Reddit](https://www.reddit.com/r/CloudFlare)
- [`@Cloudflare` on Twitter](https://twitter.com/cloudflare)
- [Facebook](https://www.facebook.com/Cloudflare)
- [YouTube](https://www.youtube.com/cloudflare-)
- [GitHub](https://github.com/cloudflare)
- [GitHub Topic](https://github.com/topics/cloudflare)
- [Stack Exchange](https://stackexchange.com/search?q=cloudflare)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/cloudflare)
- [Server Fault](https://serverfault.com/questions/tagged/cloudflare)

## Blog

- [Official Blog](https://blog.cloudflare.com)

## DNS

- [DNS Zone Files](https://github.com/irazasyed/dns-zone-files) - Ready to import common config zone files for easy configuration of various services.
- [Lexicon](https://github.com/AnalogJ/lexicon) - CLI tool to manipulate DNS records on various DNS providers in a standardized way.
- [Th3inspector](https://github.com/Moham3dRiahi/Th3inspector) - All in one CLI tool for Information Gathering.
- [Partner Panel](https://github.com/ZE3kr/Cloudflare-CNAME-Setup) - Tool for Hosting Partners to provide a DNS management panel for customers.
- [CFPMP](https://github.com/Netrvin/CFPMP) - Partner Management Panel.
- [Flares](https://github.com/lfaoro/flares) - DNS Backup Tool.
- [Block Bad Bot Ruleset](https://github.com/SukkaW/cloudflare-block-bad-bot-ruleset) - Collection of rulesets to block malicious crawlers with Firewall Rules.
- [Docker DDNS](https://github.com/oznu/docker-cloudflare-ddns) - Docker image to use the free DNS Service as a Dynamic DNS Provider.
- [DDNS script for Synology](https://github.com/joshuaavalon/SynologyCloudflareDDNS) - DDNS script for Synology NAS.
- [Dynamic DNS Bash](https://github.com/yulewang/cloudflare-api-v4-ddns) - Dynamic DNS Updater in Bash script.
- [Dynamic DNS PHP](https://github.com/lyoshenka/cloudflare-ddns) - Dynamic DNS Updater in PHP.
- [Dynamic DNS Python](https://github.com/adrienbrignon/cloudflare-ddns) - Dynamic DNS Updater in Python.
- [Multi-Provider DDNS Script](https://github.com/phuslu/ddns) - Multiple providers ddns script without dependencies.
- [Argo Tunnel Client](https://github.com/cloudflare/cloudflared) - CLI client for Argo Tunnel, a tunneling daemon that proxies any local webserver through the Cloudflare network.
- [Upper](https://github.com/ostark/upper) - Speeds up Craft dramatically using a Cache Proxy in front of your webserver.
- [Cloud Buster](https://github.com/SageHack/cloud-buster) - A comprehensive pentest tool that checks Cloudflare enabled sites for origin IP leaks.
- [CLI Tool](https://github.com/danielpigott/cloudflare-cli) - CLI tool for interacting with Cloudflare.
- [Detector](https://github.com/k4m4/cloudflare-detect) - Detect whether a site is running behind Cloudflare.
- [Scrape](https://github.com/Anorov/cloudflare-scrape) - Python module to bypass anti-bot page.
- [CloudFlair](https://github.com/christophetd/CloudFlair) - Tool to find origin servers of websites protected by CloudFlare who are publicly exposed.

## Developers

- [Developers Hub](https://developers.cloudflare.com) - Developer docs including API reference, articles, and sample code for all products.
- [Open Source](https://cloudflare.github.io) - Official Open Source Projects.
- [API Docs](https://api.cloudflare.com) - API Documentation.
- [Integration Resources](https://www.cloudflare.com/integrations) - Plugins for content management systems, control panels, cloud providers, eCommerce platforms and more.
- [Technical Resources](https://www.cloudflare.com/technical-resources) - Technical Tools and Resources.
- [The Serverlist Newsletter](https://blog.cloudflare.com/serverlist) - The Serverlist is a Cloudflare-curated newsletter about all things serverless.

## Apps

> [Cloudflare Apps](https://www.cloudflare.com/apps/developers) lets you ship your tool or service to millions of sites. Any Cloudflare customer can preview & install your code on their site in seconds.

- [Apps Directory](https://www.cloudflare.com/apps)
- [Documentation](https://www.cloudflare.com/apps/developer/docs/getting-started)
- [Developer Fund](https://www.cloudflare.com/fund)
- [App Ideas](https://github.com/cloudflare-apps/ideas)

### Open Source

- [Official OSS Apps](https://github.com/cloudflare-apps) - Collection of Official Apps.
- [Logflare](https://github.com/Logflare/cloudflare-app) - Log management & event analytics.

## Workers

> [Cloudflare Workers](https://www.cloudflare.com/products/cloudflare-workers) provides a serverless execution environment that allows you to create entirely new applications or augment existing ones without configuring or maintaining infrastructure.

### Reference

- [Documentation](https://workers.cloudflare.com/docs)
- [Tutorials](https://workers.cloudflare.com/docs/tutorials)
- [Runtime](https://workers.cloudflare.com/docs/reference/runtime)
- [Workers KV](https://workers.cloudflare.com/docs/reference/storage)

### Tools

- [Wrangler](https://github.com/cloudflare/wrangler) - `wrangler` is a CLI tool designed for folks who are interested in using Cloudflare workers.
- [Playground](https://www.cloudflareworkers.com) - Simple, instant way to preview and test code directly in the browser against any site.
- [Serverless Plugin](https://workers.cloudflare.com/docs/reference/tooling/serverless) - Plugin for [Serverless Framework](https://github.com/serverless/serverless) to develop and deploy serverless applications using Workers.
- [Worker App Kit](https://github.com/postlight/cloudflare-worker-app-kit) - Handy set of tools for creating, developing, testing, and deploying worker app.
- [GitHub Action](https://github.com/cpilsworth/cloudflare-worker-action) - Deploy a Worker on push to the master branch.
- [Workers KV Viewer](https://github.com/jroyal/cloudflare-workers-kv-viewer) - CLI based interactive viewer for Workers KV storage.
- [Redirect Management](https://forwarding.app) - Generate Redirect Worker.

### Recipes

- [Examples Collection](https://github.com/cloudflare/worker-examples) - Collection of Recipes.
- [Hello World JS Boilerplate](https://github.com/cloudflare/worker-template) - Template for kick starting a worker project in JS.
- [Hello World Rust Boilerplate](https://github.com/cloudflare/rustwasm-worker-template) - Template for kick starting a worker project using wasm-pack.
- [Router](https://github.com/cloudflare/worker-template-router) - Router that can be used with REST APIs or apps for basic routing logic.
- [Static](https://github.com/cloudflare/worker-template-static) - Generate a static HTML or JSON page from raw strings in your Workers script.
- [Fetch](https://github.com/cloudflare/worker-template-fetch) - Examples of making fetch requests and generating JSON post requests.
- [Incoming Request](https://github.com/ashleygwilliams/worker-template-requests) - Examples of reading in a POST request body of type JSON and form-data.
- [Redirect](https://github.com/cloudflare/worker-template-redirect) - Examples of sending single and bulk redirects from a Worker script.
- [Img-Color](https://github.com/xtuc/img-color-worker) - Retrieve the dominant color of a PNG or JPEG image.
- [Binast](https://github.com/xtuc/binast-cf-worker-template) - Serve BinAST via a Worker.
- [Pwnage Protection](https://github.com/detroitenglish/pw-pwnage-cfworker) - Secure Password Scoring and User Pwnage Protection API - [Usage](https://community.cloudflare.com/t/estimate-strength-of-users-new-password-input-with-zxcvbn-and-query-haveibeenpwned-for-matches-against-known-hacked-accounts/26378).
- [Cache Purger Proxy](https://gist.github.com/vdbelt/20f116236d2ebffa92f131e679c0551a) - Proxies purge cache requests - [Usage](https://community.cloudflare.com/t/worker-recipe-cache-purge-proxy/29978).
- [URL Router](https://github.com/berstend/service-worker-router) - Fast URL router - [Usage](https://community.cloudflare.com/t/open-source-fast-url-router-for-workers-js-typescript/33406).
- [Edge Proxy](https://github.com/DigitalOptimizationGroup/cloudflare-edge-proxy) - Enable A/B testing, canary releasing, gatekeeping, and SEO A/B/N testing.
- [Blue / Green Deployments](https://github.com/DigitalOptimizationGroup/blue-green-cloudflare-workers) - Working example of Blue / Green deployments with Canary releasing.
- [Preact PWA](https://github.com/DigitalOptimizationGroup/cloudflare-worker-preact-pwa) - Preact Progressive Web App.
- [CURL Interceptor](https://github.com/Gaafar/curl-worker) - Intercepts requests from `curl` command and returns something different.
- [Worker with built-in Router](https://github.com/anderly/cloudflare-worker-routing) - Allows you to separate your worker logic into different functions and/or controllers.
- [Connecting to Google Storage](https://community.cloudflare.com/t/connecting-to-google-storage/32350) - Pull Files from Google's Cloud Storage.
- [CSRF Protection](https://gist.github.com/simonerni/3501b8de6320ac37398d08d9d2d08561) - Protect any origin from CSRF by verifying Origin/Referer headers.
- [URL Query Strings Parser](https://community.cloudflare.com/t/parse-url-query-strings-with-cloudflare-workers/90286) - Parse URL query strings.
- [Regrex Replacement and Injection](https://community.cloudflare.com/t/perform-regex-replacements-and-inject-css-javascript-with-cloudflare-workers/90279) - Perform regex replacements and inject CSS/JavaScript.
- [Webpack Boilerplate](https://github.com/detroitenglish/cloudflare-workers-webpack-boilerplate) - Boilerplate to build, bundle and deploy workers with Webpack.
- [Basic Auth](https://github.com/dommmel/cloudflare-workers-basic-auth) - Protection using Basic Auth.
- [Send Logs to Logdna](https://github.com/boynet/cf-logdna-worker) - Simple recipe to send logs to logdna.
- [IP lookup service](https://github.com/matthewgall/beta.ipinfo.in) - IP Lookup service using workers.
- [Airtable Proxy](https://github.com/portable-cto/airtable-proxy-worker) - Allows you to make secure requests to the Airtable API from your frontend.
- [TypeScript Workers](https://github.com/udacity/cloudflare-typescript-workers) - Types and mocks for building a tested Typescript Worker.
- [Proxies](https://github.com/GitbookIO/proxies-on-cloudflare) - Makes it easy to build Workers, by providing high-level proxying primitives addressing common needs.
- [Static Worker](https://github.com/manatarms/static-worker) - Provides functions that make it easy to host a static website.
- [Bannero](https://github.com/nondanee/bannero) - Bannero Image API for simpledesktops.
- [Hasura](https://github.com/nathanwaters/hasura-cloudflare-worker) - Example using Facebook-based authorization and GraphQL proxy queries with Hasura.
- [IP Redirects](https://community.cloudflare.com/t/ip-redirects/18285) - Redirect users based on their IP address.
- [Switch Image to WebP](https://github.com/vidaxl-com/cloudflare_webworkers/blob/master/examples/webp.js) - Reroute image to webp when supported.
- [Geographic Routing and Load Balancer](https://community.cloudflare.com/t/geographic-routing-and-load-balancing-with-cloudflare-workers/21900) - Geographic routing and load balancing with workers.
- [UTM Tag Stripper](https://community.cloudflare.com/t/strip-utm-query-string/47941) - Strip UTM tags in query string.
- [Short URL Redirector](https://community.cloudflare.com/t/short-url-using-workers/39877) - Redirect Short URLs.
- [Repo Hunt](https://github.com/signalnerve/repo-hunt) - Find cool open-source projects daily.

# Terraform

### Recipies

## Other

- [Support](https://support.cloudflare.com)
- [System Status](https://www.cloudflarestatus.com)
- [Network Map](https://www.cloudflare.com/network)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, [Irfaq Syed](https://github.com/irazasyed) has waived all copyright and
related or neighboring rights to this work.

> Cloudflare is a registered trademark of Cloudflare, Inc.
