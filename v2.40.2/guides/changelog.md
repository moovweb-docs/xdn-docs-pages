## [v2.40.2](https://github.com/moovweb/xdn/releases/tag/untagged-cd7d16304b488fbdc279) (2021-01-21)
## What’s Changed* Fix bug in url logging where field was not escaped (#694) @phdunham* Don't populate geo/UA headers when behind edge (#693) @ierceg---
## [v2.40.1](https://github.com/moovweb/xdn/releases/tag/v2.40.1) (2021-01-18)
## What’s Changed* Add image optimizer (#686) @markbrocato* Copy over includeFiles and nodeModules before loading the router at b… (#689) @markbrocato* Preserve colors in output when running "xdn dev" (#690) @markbrocato---
## [v2.40.0](https://github.com/moovweb/xdn/releases/tag/v2.40.0) (2021-01-13)
## What’s Changed* feat(ConsoleRedirect): trim qs option + match with sorted qs (#682) @adrien-k---
## [v2.39.3](https://github.com/moovweb/xdn/releases/tag/v2.39.3) (2021-01-11)
## What’s Changed* bump version (#685) @KaarelKelk* fix(Axios) Fix failing deploymnts due to maxBodyLength (#684) @KaarelKelk---
## [v2.39.2](https://github.com/moovweb/xdn/releases/tag/v2.39.2) (2021-01-11)
## What’s Changed* XDN-8150 - Wrong route being run when proxy is used with path and tra… (#683) @markbrocato---
## [v2.39.1](https://github.com/moovweb/xdn/releases/tag/v2.39.1) (2021-01-11)
## What’s Changed* fix(Build): double logs on build fail + external messages (#681) @adrien-k---
## [v2.39.0](https://github.com/moovweb/xdn/releases/tag/v2.39.0) (2021-01-08)
## What’s Changed* Add support for nuxt generate and static pages which fall back to SSR. (#671) @markbrocato---
## [v2.38.1](https://github.com/moovweb/xdn/releases/tag/v2.38.1) (2021-01-08)
## What’s Changed* Fixing VSF (#676) @dijs---
## [v2.38.0](https://github.com/moovweb/xdn/releases/tag/v2.38.0) (2021-01-08)
## What’s Changed* XDN-8116_XDN-cli-process-should-reflect-same-exit-code-as-its-child-process_Markus-Tarn (#680) @MarkusTarn* Adds a --connector option to xdn init. (#679) @markbrocato* Don't allow built-in envvars to be overriden through dev console (#677) @ierceg---
## [v2.37.2](https://github.com/moovweb/xdn/releases/tag/v2.37.2) (2021-01-07)
## What’s Changed* [XDN-7802] Republish connectors to public repo (#665) @tristanlee85* Fix local permanent asset support in dev and prod modes. (#678) @markbrocato
---
## [v2.37.1](https://github.com/moovweb/xdn/releases/tag/v2.37.1) (2021-01-06)
## What’s Changed* Increase default header size to 64kb (#669) @ierceg* Xdn 7974 fix include files (#670) @markbrocato* Fix regression in 2.34 where renderNextPage with rewritten path fails to render in dev mode. (#667) @markbrocato---
## [v2.37.0](https://github.com/moovweb/xdn/releases/tag/v2.37.0) (2021-01-06)
## What’s Changed* Bump axios from 0.19.0 to 0.21.1 in /packages/cli (#675) @dependabot* Bump axios from 0.19.2 to 0.21.1 in /packages/build-lambda (#674) @dependabot* feat: Preserve Cache + permanent assets (#645) @adrien-k* Don't cache fallback route for Angular/Spartacus (#672) @kevhender* fix x-xdn-destination destinationName escape in edge_recv_evaluate_de… (#673) @KaarelKelk* fix(Prerender) fix types (#668) @KaarelKelk* User lambda errors during deployment are not reported to CLI (#648) @MarkusTarn---
## [v2.36.1](https://github.com/moovweb/xdn/releases/tag/v2.36.1) (2020-12-30)
## What’s Changed* Fix redirects with queries (#666) @ierceg---
## [v2.36.0](https://github.com/moovweb/xdn/releases/tag/v2.36.0) (2020-12-30)
## What’s Changed* core API docs update (#663) @ianand* Use xdn dev (#660) @markbrocato---
## [v2.35.2](https://github.com/moovweb/xdn/releases/tag/v2.35.2) (2020-12-24)
## What’s Changed* Xdn 7579 xdn init doesnt create dependency files mark brocato (#656) @markbrocato---
## [v2.35.1](https://github.com/moovweb/xdn/releases/tag/v2.35.1) (2020-12-23)
## What’s Changed* Fix caching manifest generation issue (#661) @ierceg* fix(proxy/edge): path with no / + fix(proxy/cloud) query-string forwarding (#662) @adrien-k* fix(Prerendering) fix retry (#655) @KaarelKelk* Bump ini from 1.3.5 to 1.3.8 in /packages/build-lambda (#659) @dependabot---
## [v2.35.0](https://github.com/moovweb/xdn/releases/tag/v2.35.0) (2020-12-22)
## What’s Changed* XDN-7844 - Issues with Next Commerce support (#658) @markbrocato* XDN-7849 - serveStatic does not support nested paths (#657) @markbrocato* Introduce a formal XDN connectors API (#637) @markbrocato
---
## [v2.34.2](https://github.com/moovweb/xdn/releases/tag/v2.34.2) (2020-12-22)
## What’s Changed* Add checks before using endsWith (#651) @ierceg---
## [v2.34.1](https://github.com/moovweb/xdn/releases/tag/v2.34.1) (2020-12-21)
## What’s Changed* Fastly cert update + multiple domain activation fix (#653) @leotoll---
## [v2.34.0](https://github.com/moovweb/xdn/releases/tag/v2.34.0) (2020-12-21)
## What’s Changed* Improved error message if project fails due to missing @xdn/next build plugins (#652) @ianand* XDN-7810 - Add support for fallback: 'blocking' in getStaticPaths() (#654) @markbrocato---
## [v2.33.4](https://github.com/moovweb/xdn/releases/tag/v2.33.4) (2020-12-18)
## What’s Changed* Remove content-length setting on unzipping (#601) @ierceg---
## [v2.33.3](https://github.com/moovweb/xdn/releases/tag/v2.33.3) (2020-12-17)
## What’s Changed* Added missing appShell (#649) @ierceg---
## [v2.33.2](https://github.com/moovweb/xdn/releases/tag/v2.33.2) (2020-12-17)
## What’s Changed* fix(Redirect): bug in initialise build (#647) @adrien-k* test(ConsoleRedirect): enable integration test (#646) @adrien-k* Do not reenable clustering and shielding on ISG+deployment restarts (#643) @ierceg---
## [v2.33.1](https://github.com/moovweb/xdn/releases/tag/v2.33.1) (2020-12-16)
## What’s Changed* XDN-7693 - Next: SSG static data paths are not correctly prerendered (#644) @markbrocato* fix(core/redirect): query params (fixes the devtools docs redirect) (#608) @adrien-k---
## [v2.33.0](https://github.com/moovweb/xdn/releases/tag/v2.33.0) (2020-12-16)
## What’s Changed* Localized rewrites not working in next commerce app (#641) @markbrocato* feat(redirects): implement global redirects (#627) @adrien-k---
## [v2.32.2](https://github.com/moovweb/xdn/releases/tag/v2.32.2) (2020-12-15)
## What’s Changed* Don't set long TTL on revalidated assets (#640) @ierceg* XDN-7650 - Route for /__xdn__/cache-manifest.js fails if  route is de… (#639) @markbrocato* XDN-7592 - Build fails when serveStatic points to a non-existing asset. (#633) @markbrocato---
## [v2.32.1](https://github.com/moovweb/xdn/releases/tag/v2.32.1) (2020-12-11)
## What’s Changed* Log AWS subaccount ID to our Sumo access logs (#638) @ierceg* Prohibit the manipulation of content-length header directly from the router (#635) @ierceg* feat(Prerender) dump body on 534 (#636) @KaarelKelk---
## [v2.32.0](https://github.com/moovweb/xdn/releases/tag/v2.32.0) (2020-12-11)
## What’s Changed* Adds renderWithApp ResponseWriter method. (#634) @markbrocato* Fix decoding of params for prefetch when values already have a % sign (#630) @kevhender---
## [v2.31.0](https://github.com/moovweb/xdn/releases/tag/v2.31.0) (2020-12-10)
## What’s Changed* Fix integration tests (#631) @ierceg* Enable ISG (#600) @ierceg* fix(Actions) test new workflow env variable (#629) @KaarelKelk---
## [v2.30.1](https://github.com/moovweb/xdn/releases/tag/v2.30.1) (2020-11-16)
## What’s Changed* Fix another cache poisoning (#611) @ierceg---
## [v2.30.0](https://github.com/moovweb/xdn/releases/tag/v2.30.0) (2020-11-16)
## What’s Changed* @xdn/apollo now supports converting queries to GETs by operation and compressing them. (#560) @markbrocato* The @xdn/next plugin now supports webpack 5. (#603) @markbrocato* xdn init now supports TypeScript (#607) @markbrocato* XDN-6813 - Webpack fails on importing of @xdn/core (#605) @markbrocato---
## [v2.29.0](https://github.com/moovweb/xdn/releases/tag/v2.29.0) (2020-11-10)
## What’s Changed* [XDN-6213] Spartacus integration improvement - first steps (#598) @kevhender---
## [v2.28.0](https://github.com/moovweb/xdn/releases/tag/v2.28.0) (2020-11-06)
## What’s Changed* XDN-6756 - Support distDir in next.config.js (#599) @markbrocato---
## [v2.27.4](https://github.com/moovweb/xdn/releases/tag/v2.27.4) (2020-11-04)
## What’s Changed* Fix Module decode-uri-component not found (#595) @markbrocato---
## [v2.27.3](https://github.com/moovweb/xdn/releases/tag/v2.27.3) (2020-11-04)
## What’s Changed* Always log user agent in user facing logs (#594) @ierceg* Add __dev__getCompleteEdgeConfig job (#593) @ierceg* Fix using custom servers in development. (#589) @markbrocato---
## [v2.27.2](https://github.com/moovweb/xdn/releases/tag/v2.27.2) (2020-11-04)
## What’s Changed* XDN-6589 Fix browser.maxAge: 0 interfering with edge caching (#590) @ierceg---
## [v2.27.1](https://github.com/moovweb/xdn/releases/tag/v2.27.1) (2020-11-04)
## What’s Changed* Bump version to 2.27.1 (#591) @KaarelKelk* XDN-6513_Edge-config-validation-errors-are-not-properly-shown-to-the-user_Markus-Tarn (#587) @MarkusTarn* feat(Prerendering) log response (#582) @KaarelKelk* Fix `browser.maxAge: 0` interfering with edge caching (#588) @ierceg
---
## [v2.27.0](https://github.com/moovweb/xdn/releases/tag/v2.27.0) (2020-11-03)
## What’s Changed* Allow users to run downloaded deployments. (#576) @markbrocato* fix(Devtools): preserve original req (#586) @adrien-k* chore(build-lambda): remove secrets from logs + remove altHostnames +… (#584) @adrien-k* XDN-6217_Raise-an-error-durring-deployment-if-any-of-the-backends-use-one-of-the-sites-domains-as-domainOrIp_Markus-Tarn (#573) @MarkusTarn* XDN-6397 - Add source maps to router bundle to making debugging easie… (#580) @markbrocato---
## [v2.26.3](https://github.com/moovweb/xdn/releases/tag/v2.26.3) (2020-10-28)
## What’s Changed* Log x-xdn-hit-request-id (#583) @ierceg---
## [v2.26.2](https://github.com/moovweb/xdn/releases/tag/v2.26.2) (2020-10-28)
## What’s Changed* Fix watching of links for prefetching (#585) @kevhender---
## [v2.26.1](https://github.com/moovweb/xdn/releases/tag/v2.26.1) (2020-10-27)
## What’s Changed* fix(Prefetcher): check origin (#581) @adrien-k---
## [v2.26.0](https://github.com/moovweb/xdn/releases/tag/v2.26.0) (2020-10-26)
## What’s Changed* Add more logging on edge signature check (#571) @ierceg* feat(FastlyClient): retry on clone 409 (#579) @adrien-k* chore(lint): cover and fix ts files (#561) @adrien-k* XDN-5841_Allow-string-for-headercookiequery-matching-not-just-Regex_Markus-Tarn (#558) @MarkusTarn---
## [v2.25.0](https://github.com/moovweb/xdn/releases/tag/v2.25.0) (2020-10-23)
## What’s Changed* Emulate edge locally by adding parameter interpolation in response.setHeader (#467) @phdunham* Update @xdn/prefetcher to check query parameters (CU-XDN-514) (CU-XDN-5937) (#539) @kevhender---
## [v2.24.2](https://github.com/moovweb/xdn/releases/tag/v2.24.2) (2020-10-23)
## What’s Changed* Fix logo (#574) @ierceg* fix(Devtools): isolate Devtools style + fix reload + add clear btns (#570) @adrien-k* Raise 500 when router path matching is bad including partial splats (#556) @ierceg---
## [v2.24.1](https://github.com/moovweb/xdn/releases/tag/v2.24.1) (2020-10-21)
## What’s Changed* Preloading logs (#566) @KaarelKelk---
## [v2.24.0](https://github.com/moovweb/xdn/releases/tag/v2.24.0) (2020-10-21)
## What’s Changed* fix(withXDN): try fixing integration tests (#569) @adrien-k* fix(Preloading) when no requests are sent back to le-deployer (#563) @KaarelKelk* Fix XDN reentry when clients forward all the headers including Fastly-FF (#567) @ierceg* feat(Devtools): Allow enabling/disabling the devtools (#554) @adrien-k* Adds xdn.config.js to the src directory in the uploaded bundle. (#568) @markbrocato* Fix the bad header name in Spartacus package (#565) @ierceg---
## [v2.23.1](https://github.com/moovweb/xdn/releases/tag/v2.23.1) (2020-10-19)
## What’s Changed* fix(Build-lambda): override stable-2 (#564) @adrien-k---
## [v2.22.0](https://github.com/moovweb/xdn/releases/tag/v2.22.0) (2020-10-19)
## What’s Changed* Bump version to 2.22.0 (#562) @KaarelKelk* feat(Preloading) Adds a static prerendering option to Router (#458) @markbrocato* XDN-5390_Validate-domain-names_Markus-Tarn (#553) @MarkusTarn* Update readme to reflect spartacus integration tests required maintenance work (#538) @leotoll* Fix next peerDependency in @xdn and automatically add @xdn/svelte whe… (#535) @markbrocato* chore(prettier): harmonize prettier and format more file types (#547) @adrien-k* fix(Fastly): expose invalid backend domain error (#550) @adrien-k* Remove xdn_pref_headers param (#518) @kevhender* feat(Devtools/Visualizer) (#509) @adrien-k---
## [v2.21.0](https://github.com/moovweb/xdn/releases/tag/v2.21.0) (2020-10-14)
## What’s Changed* Add req.protocol (#551) @ierceg---
## [v2.20.3](https://github.com/moovweb/xdn/releases/tag/v2.20.3) (2020-10-13)
## What’s Changed* Do not leak auth header upstream (#549) @ierceg* fix(CallbackApi): fix awaitFlushed, add timeout and retry + unit tests (#543) @adrien-k---
## [v2.20.2](https://github.com/moovweb/xdn/releases/tag/v2.20.2) (2020-10-07)
## What’s Changed* Fix trailing query string in lambda (#546) @ierceg* Make `createGroups` param of `addCookie` optional (#540) @kevhender---
## [v2.20.1](https://github.com/moovweb/xdn/releases/tag/v2.20.1) (2020-10-06)
## What’s Changed* fix(CallbackLogger) fixed message flush race condition (#542) @KaarelKelk* Fix initialization build problem (#544) @ierceg---
## [v2.20.0](https://github.com/moovweb/xdn/releases/tag/v2.20.0) (2020-10-06)
## What’s Changed* Allow opt-in support for HTTP protocol (#533) @ierceg---
## [v2.19.0](https://github.com/moovweb/xdn/releases/tag/v2.19.0) (2020-10-05)
## What’s Changed* XDN-5643 - Environment variables from the XDN Developer Console are now accessible at build time when using a deploy token (#526) @markbrocato---
## [v2.18.1](https://github.com/moovweb/xdn/releases/tag/v2.18.1) (2020-10-05)
## What’s Changed* Fix error with babel-loader not being found in Next.js apps starting … (#536) @markbrocato---
## [v2.18.0](https://github.com/moovweb/xdn/releases/tag/v2.18.0) (2020-10-02)
## What’s Changed* Add --includeSources CLI option. (#523) @markbrocato* XDN-5761 - Add @xdn/react when running xdn init in gatsby app (#534) @markbrocato* XDN-5749 - Improve XDN install time by removing serverless (#531) @markbrocato* XDN-5753 - Fix issue with websocket requests failing during local dev… (#532) @markbrocato
---
## [v2.17.0](https://github.com/moovweb/xdn/releases/tag/v2.17.0) (2020-10-01)
## What’s Changed* XDN-5686 - Minimize Nuxt.js serverless bundle size (#528) @markbrocato* Minimize router bundle size (#529) @markbrocato* Send custom message for Fastly 500 errors (#524) @ierceg---
## [v2.16.1](https://github.com/moovweb/xdn/releases/tag/v2.16.1) (2020-09-30)
## What’s Changed* Enable build lambda deploys to sandbox (#527) @ierceg* Nuxt: static routes should take precedence over dynamic routes. (#525) @markbrocato* Use random fastly API tokens provided by LD, if available (#508) @ierceg* Fix console output to JSON doesn't capture all args (#521) @ierceg* XDN-5466 - Embed the router in the uploaded build (#514) @markbrocato---
## [v2.16.0](https://github.com/moovweb/xdn/releases/tag/v2.16.0) (2020-09-28)
## What’s Changed* XDN-3005 - Support for basic auth (#519) @markbrocato* XDN-5587 - Fix issue where catch-all routes incorrectly take preceden… (#520) @markbrocato* Improve error message that is shown when deployment fails due to an error in the user's application code. (#517) @markbrocato* Improve user errors on edge deploy (#502) @MarkusTarn* Add integration tests for force-private-caching override (#513) @ierceg---
## [v2.15.0](https://github.com/moovweb/xdn/releases/tag/v2.15.0) (2020-09-25)
## What’s Changed* Added paths config support (#515) @dijs* Allow backends to have custom ports at and above 443 (#516) @ierceg---
## [v2.14.0](https://github.com/moovweb/xdn/releases/tag/v2.14.0) (2020-09-24)
## What’s Changed* Allow for not-present matching for headers, cookies and query parameters (#511) @ierceg* Fix header name comparison to be case-insensitive (#511) @ierceg---
## [v2.13.4](https://github.com/moovweb/xdn/releases/tag/v2.13.4) (2020-09-24)
## What’s Changed* Reset private caching to false only if explicitly requested in the router (#512) @ierceg---
## [v2.13.3](https://github.com/moovweb/xdn/releases/tag/v2.13.3) (2020-09-24)
## What’s Changed* XDN-5528 - Support hardcoded paths in Next.js rewrites (#510) @markbrocato---
## [v2.13.2](https://github.com/moovweb/xdn/releases/tag/v2.13.2) (2020-09-23)
## What’s Changed* Improve CLI output: Add a clearer deployment complete message. (#505) @markbrocato---
## [v2.13.1](https://github.com/moovweb/xdn/releases/tag/v2.13.1) (2020-09-23)
## What’s Changed* Don't add default router and service worker to the user's app on ever… (#507) @markbrocato---
## [v2.13.0](https://github.com/moovweb/xdn/releases/tag/v2.13.0) (2020-09-22)
## What’s Changed* [XDN-5422] Ensure that manual edits to the changelog are preserved (#506) @tristanlee85* XDN-5414 - Use --standalone to bundle dependencies when running nuxt … (#501) @markbrocato---
## [v2.12.1](https://github.com/moovweb/xdn/releases/tag/v2.12.1) (2020-09-22)
## What’s Changed* Update Sapper integration test to match the docs and not include node… (#504) @markbrocato* Remove obsolete domain check to enable wildcard reverse proxy in edge (#503) @ierceg* Allow relative paths when deep fetching from JSON (#498) @kevhender---
## [v2.12.0](https://github.com/moovweb/xdn/releases/tag/v2.12.0) (2020-09-21)
## What’s Changed* Apollo prefetching now uses GETs for all queries. (#500) @markbrocato---
## [v2.11.2](https://github.com/moovweb/xdn/releases/tag/v2.11.2) (2020-09-21)
## What’s Changed* Fix XDN-5364 - Next.js redirect to remove trailing slash prevents fal… (#496) @markbrocato* feat(CLI): Require node version: 12 or newer (#495) @adrien-k* [XDN-5258] Generate changelog when publishing release (#497) @tristanlee85* docs(README): add link to docs (#499) @adrien-k---
## [v2.11.1](https://github.com/moovweb/xdn/releases/tag/v2.11.1) (2020-09-16)
## What’s Changed* Update integration tests for POST/GET&xdn_prefetch=1 caching (#494) @phdunham* Next.js: Fix xdn build on windows (#492) @markbrocato* Fix coverage of nextRoutes (#493) @leotoll---
## [v2.11.0](https://github.com/moovweb/xdn/releases/tag/v2.11.0) (2020-09-16)
## What’s Changed* feat(frameworks): add Gatsby support + serve static root document (#474) @adrien-k---
## [v2.10.3](https://github.com/moovweb/xdn/releases/tag/v2.10.3) (2020-09-15)
## What’s Changed* Sapper: Remove extra service-worker route from the default routes.js file add… (#491) @markbrocato---
## [v2.10.2](https://github.com/moovweb/xdn/releases/tag/v2.10.2) (2020-09-15)
## What’s Changed* Next.js: pages/404.js now properly functions as the default fallback (#478) @leotoll* Fix bug in @xdn/sapper where the service worker would not be loaded i… (#490) @markbrocato---
## [v2.10.1](https://github.com/moovweb/xdn/releases/tag/v2.10.1) (2020-09-14)
## What’s Changed* Fix issue where pages/api/index.js was not being resolved by the XDN … (#488) @markbrocato---
## [v2.10.0](https://github.com/moovweb/xdn/releases/tag/v2.10.0) (2020-09-14)
## What’s Changed* feat(Errors): enhance user-facing fastly errors (#480) @adrien-k* Fix bug when using proxy with path option and a catch-all or optional… (#482) @markbrocato* Run request/response header manipulation in compute/trasnform (#483) @ierceg* Add functionality for prefetching GQL requests. (CU-a6axpw) (#451) @markbrocato* Add x-xdn-user-t to server-timing response header (#484) @ierceg* Bump node-fetch from 2.6.0 to 2.6.1 in /integration-tests/edge (#487) @dependabot* Bump node-fetch from 2.6.0 to 2.6.1 in /packages/core (#486) @dependabot* Add support for running Sapper apps with xdn run --production (#481) @markbrocato* Log 503 errors generated by shield (not just edge) (#479) @phdunham---
## [v2.9.0](https://github.com/moovweb/xdn/releases/tag/v2.9.0) (2020-09-09)
## What’s Changed* Fix XDN-on-XDN caching issues (#431) @ierceg* fix(MatchQuery) added edge config tests (#477) @KaarelKelk---
## [v2.8.0](https://github.com/moovweb/xdn/releases/tag/v2.8.0) (2020-09-08)
## What’s Changed* Adds support for the Sapper framework (#462) @markbrocato* feat(CLI): log failed build output in LD (#452) @adrien-k* Bump yargs-parser from 15.0.0 to 15.0.1 in /packages/cli (#475) @dependabot---
## [v2.7.0](https://github.com/moovweb/xdn/releases/tag/v2.7.0) (2020-09-07)
## What’s Changed* feat(MatchQuery) added criteria.query to match query params - XDN-533 (#461) @KaarelKelk* Optimize router loop unrolling by using equivalency chains (#472) @ierceg* fix(handler/logs): wrap console AND streams + remove globals (#471) @adrien-k* fix(Route) Matching headers returned true for single header match (#469) @KaarelKelk---
## [v2.6.4](https://github.com/moovweb/xdn/releases/tag/v2.6.4) (2020-09-04)
## What’s Changed* Lower the ACL limit to 900 to avoid Fastly's spurious API errors (#473) @ierceg---
## [v2.6.3](https://github.com/moovweb/xdn/releases/tag/v2.6.3) (2020-09-03)
## What’s Changed* Move static method to RouteGroup (#465) @markbrocato---
## [v2.6.2](https://github.com/moovweb/xdn/releases/tag/v2.6.2) (2020-09-02)
## What’s Changed* Fix bug where xdn init fails if a supported web framework is not dete… (#470) @markbrocato* Ignore query params when watching links to prefetch (#444) @kevhender---
## [v2.6.1](https://github.com/moovweb/xdn/releases/tag/v2.6.1) (2020-09-02)
## What’s Changed* Optimize x-xdn-original-qs to be injected only when qs are changed (#468) @ierceg---
## [v2.6.0](https://github.com/moovweb/xdn/releases/tag/v2.6.0) (2020-09-01)
## What’s Changed* Fix caching of static pages in NextRoutes. (#464) @markbrocato* Fix memory overconsumption in moov_hash (#463) @ierceg* Router static implementation for next (#428) @leotoll* Improve ci time (#447) @leotoll* Inject example x-xdn-geo- headers when running locally for easier testing. (#460) @phdunham* Emulate edge by injecting headers based on user-agent (#457) @phdunham---
## [v2.5.0](https://github.com/moovweb/xdn/releases/tag/v2.5.0) (2020-08-28)
## What’s Changed* feat(core/Router): prevent adding routes after fallback statement (#453) @adrien-k* fix(consoleWrapper): shim stdout/stderr to encapsulate in json (#432) @adrien-k* XDN-1438 - Fix bug where using an async callback in compute() results… (#456) @markbrocato* fix(@xdn/angular) Fix link command (#436) @KaarelKelk* Update the color scheme of the logo in the CLI. (#455) @markbrocato* Emulate edge's x-xdn-client-ip header when running locally (#454) @phdunham---
## [v2.4.2](https://github.com/moovweb/xdn/releases/tag/v2.4.2) (2020-08-26)
## What’s Changed* Corrected API documentation comment (#450) @ianand* Order predefined routes before dynamic routes (#440) @dijs* Angular fixups (#446) @tonylepmets---
## [v2.4.1](https://github.com/moovweb/xdn/releases/tag/v2.4.1) (2020-08-26)
## What’s Changed* PC-2330 - add Fastly API retry on 500 or 503 errors (#441) @phdunham* Disable request coalesing on shield (#448) @ierceg---
## [v1.48.1](https://github.com/moovweb/xdn/releases/tag/v1.48.1) (2020-08-26)
## What’s Changed* [v1 back port] Disable request coalescing on shield (#449) @ierceg---
## [v2.4.0](https://github.com/moovweb/xdn/releases/tag/v2.4.0) (2020-08-26)
## What’s Changed* Fix bug where context.params was undefined in getServerSideProps and getInitialProps in development when using xdn run.  (#443) @dijs* Adds a `compute()` function to `ResponseWriter` to compute responses in t… (#442) @markbrocato* Support service workers and prefetching in Nuxt apps when running in … (#445) @markbrocato---
## [v1.48.0](https://github.com/moovweb/xdn/releases/tag/v1.48.0) (2020-08-24)
## What’s Changed* v1: Add ability to completely turn off edge/browser caching for a route (back port of #435 to v1) (#437) @ierceg* Don't use latest tag any more (#434) @ierceg---
## [v2.3.1](https://github.com/moovweb/xdn/releases/tag/v2.3.1) (2020-08-23)
## What’s Changed* No changes - releasing as the previous release went out incorrectly as 2.2.1---
## [v2.3.0](https://github.com/moovweb/xdn/releases/tag/v2.3.0) (2020-08-22)
## What’s Changed* Add ability to completely turn off edge/browser caching for a route (#435) @ierceg---
## [v1.47.0](https://github.com/moovweb/xdn/releases/tag/v1.47.0) (2020-08-21)
## What’s Changed* [1.x] Adds a new timing API to allow users to track the performance of thei… (#430) (#433) @ierceg---
## [v2.2.0](https://github.com/moovweb/xdn/releases/tag/v2.2.0) (2020-08-20)
## What’s Changed* Adds a new timing API to allow users to track the performance of thei… (#430) @markbrocato* Upgrade next tests to 9.5 (#429) @ierceg* Fix issue during xdn build with Next.js apps that use source maps. (#423) @markbrocato* Add service worker to new Nuxt.js apps. (#427) @markbrocato* Fix bug when Next.js rewrites and redirects functions are async. (#425) @markbrocato---
## [v2.1.0](https://github.com/moovweb/xdn/releases/tag/v2.1.0) (2020-08-18)
## What’s Changed* Install @xdn/vue as a runtime dependency. (#421) @markbrocato* Make cors config optional for prefetch options (#424) @kevhender* Fix VCL code generation with conditions containing double quotes (#426) @ierceg* Add spartacus tests (#415) @leotoll* Make cors config optional for prefetch options (#420) @kevhender* Update "current" folder with latest when pushing new docs (#422) @kevhender---
## [v2.0.4](https://github.com/moovweb/xdn/releases/tag/v2.0.4) (2020-08-17)
## What’s Changed* Add NODE_ENV production to build lambdas (#419) @ierceg* Add appShell method to ResponseWriter. (#413) @markbrocato* PC-2313 - Fix nuxt es6 prod (#418) @markbrocato---
## [v2.0.3](https://github.com/moovweb/xdn/releases/tag/v2.0.3) (2020-08-15)
## What’s Changed* Support src/pages in Next.js apps. (#417) @markbrocato
