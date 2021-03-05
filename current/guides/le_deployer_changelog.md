## [v1.40.3](https://github.com/moovweb/le-deployer/releases/tag/v1.40.3) (2021-03-03)
## What’s Changed* Fix creating log entry on site (#738) @KaarelKelk---
## [v1.40.2](https://github.com/moovweb/le-deployer/releases/tag/v1.40.2) (2021-03-02)
## What’s Changed* Fix ssl data transfer (#735) @leotoll---
## [v1.40.1](https://github.com/moovweb/le-deployer/releases/tag/v1.40.1) (2021-03-02)
## What’s Changed* Fix ssl data migration (#734) @leotoll---
## [v1.40.0](https://github.com/moovweb/le-deployer/releases/tag/v1.40.0) (2021-03-02)
## What’s Changed* SSL generation/renewal (#657) @leotoll* fix(PrefetchHealth) fix error when there's no prod deployment (#725) @KaarelKelk* fix(Metrics) Support old fallback syntax for xdn route (#726) @KaarelKelk* Wrap query param misses column (#693) @kevhender* Fix column overflow for route details table (#692) @kevhender* Keep table from jumping while loading spinner is displayed (#694) @kevhender---
## [v1.39.1](https://github.com/moovweb/le-deployer/releases/tag/v1.39.1) (2021-02-25)
## What’s Changed* Prefetch fix and clean up (#716) @dijs---
## [v1.39.0](https://github.com/moovweb/le-deployer/releases/tag/v1.39.0) (2021-02-25)
## What’s Changed* Fix Cache hit rate shown as NaN (#714) @KaarelKelk* Fix prefetch health % values below chart (#697) @KaarelKelk* Fix inconsistent Cache Hit Rate calculation (#685) @KaarelKelk* fix(CreateEnvironment) Fixed validaton on create environment (#679) @KaarelKelk* Update tooltip for traffic col in route details table (#691) @kevhender* Open latest deployment link in new tab - XDN-8920 (#690) @kevhender* Added show all activity link to overview pages (#684) @KaarelKelk* Show only full cache flushes in  hit rate over time (#683) @KaarelKelk* Fix converting xdn routejson to router syntax (#686) @KaarelKelk* Prefetch health (#645) @dijs* Fix issue where the left edge of card shadows is visible when the loa… (#680) @markbrocato* Fix Site Overview Url and environment name (#682) @KaarelKelk* Format routes and ttls as code. (#681) @markbrocato* Added IAM permissions and Environment Variables for CertRenewal integration (#674) @Th0masL---
## [v1.38.1](https://github.com/moovweb/le-deployer/releases/tag/v1.38.1) (2021-02-17)
## What’s Changed* Fixed site overview when no production environment deployment exists (#672) @KaarelKelk* Migration fix for nested s3 download path (#632) @leotoll* Ignore parameters files (#670) @Th0masL* XDN-7880_Allow-users-to-delete-unused-permalinks_Markus-Tarn (#658) @MarkusTarn---
## [v1.38.0](https://github.com/moovweb/le-deployer/releases/tag/v1.38.0) (2021-02-12)
## What’s Changed* Format TTLs for route details page (#663) @kevhender* Fix for wildcard validation (#662) @leotoll* Replaced all mentions of build with deployment (#654) @dijs* Add xbp domain for xdn jobs payload (#656) @KaarelKelk* Hide Path Variability panel (#661) @kevhender* Added tooltip for ttl values in metrics (#659) @KaarelKelk* Caching Tab v1 (#652) @kevhender---
## [v1.37.1](https://github.com/moovweb/le-deployer/releases/tag/v1.37.1) (2021-02-05)
## What’s Changed* Fixed chart when no data is available (#651) @KaarelKelk---
## [v1.37.0](https://github.com/moovweb/le-deployer/releases/tag/v1.37.0) (2021-02-05)
## What’s Changed* Hit rate over time (#649) @KaarelKelk* cherry picked 23afb3681802374be86f2c69764fa736a2facd32 from ajay's pr (#650) @markbrocato* Fixed tab navigation issues (#646) @dijs---
## [v1.36.0](https://github.com/moovweb/le-deployer/releases/tag/v1.36.0) (2021-02-03)
## What’s Changed* Site Overview Page (#597) @dijs---
## [v1.35.3](https://github.com/moovweb/le-deployer/releases/tag/v1.35.3) (2021-02-03)
## What’s Changed* XDN-6930_Using-CLI-to-clear-path-from-cache-with-funky-characters-causes-an-error_Markus-Tarn (#637) @MarkusTarn* fix(SplitTestingRules) fix IE from browser options (#642) @KaarelKelk---
## [v1.35.2](https://github.com/moovweb/le-deployer/releases/tag/v1.35.2) (2021-02-01)
## What’s Changed* Fixed z-index issue on environments page (#638) @dijs* fix(EnvironmentByName): allow nil team_slug for CLI (#639) @adrien-k---
## [v1.35.1](https://github.com/moovweb/le-deployer/releases/tag/v1.35.1) (2021-02-01)
## What’s Changed* Only page XDN Support when site is down (#640) @kevhender---
## [v1.35.0](https://github.com/moovweb/le-deployer/releases/tag/v1.35.0) (2021-01-28)
## What’s Changed* [CLOUDFORMATION] feat(LogShipping): internal buckets endpoint (#634) @adrien-k* Add additional Pager Duty API tokens to notify multiple teams (#635) @kevhender---
## [v1.34.0](https://github.com/moovweb/le-deployer/releases/tag/v1.34.0) (2021-01-26)
## What’s Changed* Add help page with Intercom API connection (#603) @kevhender---
## [v1.33.1](https://github.com/moovweb/le-deployer/releases/tag/v1.33.1) (2021-01-25)
## What’s Changed* Fix(GithubAction): prod release
---
## [v1.33.0](https://github.com/moovweb/le-deployer/releases/tag/v1.33.0) (2021-01-25)
## What’s Changed* add XDN VERSION to airbrake error (#631) @adrien-k* chore(*): automate prod db migration (#619) @adrien-k* feat(LambdaJob): add build console url to airbrake (#628) @adrien-k* fix(EnvVariables): copy secret flag on draft and clone (#630) @adrien-k* feat(MetricsClient) fix status code check (#629) @KaarelKelk* [MIGRATION] chore(FeatureFlag): move out of DB (#627) @adrien-k---
## [v1.32.0](https://github.com/moovweb/le-deployer/releases/tag/v1.32.0) (2021-01-19)
## What’s Changed* Cloudformation! feat(PrerenderTop) added metrics service to prerender payload (#570) @KaarelKelk* fix(Activity): subscriptions not unregistering on unmount (#625) @adrien-k* chore(ECS): set app desired count to 4 (#624) @adrien-k---
## [v1.31.1](https://github.com/moovweb/le-deployer/releases/tag/v1.31.1) (2021-01-13)
## What’s Changed* fix prod rails console upgrade
---
## [v1.31.0](https://github.com/moovweb/le-deployer/releases/tag/v1.31.0) (2021-01-13)
## What’s Changed* Build retry (#598) @leotoll* [MIGRATION] Add screen for invited users to reset/link password (#611) @leotoll* Added shortcut activate button to bottom on env config (#612) @dijs---
## [v1.30.0](https://github.com/moovweb/le-deployer/releases/tag/v1.30.0) (2021-01-13)
## What’s Changed* fix(GraphQL) Fix page size for demo team (#622) @KaarelKelk* chore(EnvVersion/redirects): remove qs from original request (#621) @adrien-k* Refine pardot/mixpanel signup attributes (#604) @leotoll* Report user lambda errors to cli 2 (#610) @MarkusTarn* chore(deps): bump nokogiri from 1.10.10 to 1.11.1 (#618) @dependabot* [MIGRATION] feat(FeatureFlag): optional min subaccount version (#609) @adrien-k* fix(Build): initial build when team has no aws_account yet (#615) @adrien-k* feat(Dev): auto-migration + restart on sandbox (#607) @adrien-k* chore(deps): bump axios from 0.19.2 to 0.21.1 in /mocks (#614) @dependabot---
## [v1.29.3](https://github.com/moovweb/le-deployer/releases/tag/v1.29.3) (2021-01-06)
## What’s Changed* fix featureFlag enable (#617) @adrien-k---
## [v1.29.2](https://github.com/moovweb/le-deployer/releases/tag/v1.29.2) (2021-01-06)
## What’s Changed* fix(KeepCache): wording---
## [v1.29.1](https://github.com/moovweb/le-deployer/releases/tag/v1.29.1) (2021-01-05)
## What’s Changed* fix(SplitTesting) UI fixes (#613) @KaarelKelk* fix(PreserveCache): keep value on new draft (#608) @adrien-k---
## [v1.29.0](https://github.com/moovweb/le-deployer/releases/tag/v1.29.0) (2020-12-21)
## What’s Changed* Fix UI for deploy token actions (#606) @KaarelKelk* feat(PermanentAssets): add backend to metrics (#605) @adrien-k* feat(Prerendering) trigger prerendering after cache flush (#540) @KaarelKelk* feat(PreserveCache): UI, API and build-lambda payload + feature flags + some cool ECS scripts (#593) @adrien-k* Update migration instructions (#602) @ierceg* feat(Redirect): UI enhancements (#600) @adrien-k* Report user lambda errors to CLI (#596) @MarkusTarn---
## [v1.28.1](https://github.com/moovweb/le-deployer/releases/tag/v1.28.1) (2020-12-17)
## What’s Changed* fix(Redirects): minor UI bugs (#599) @adrien-k---
## [v1.28.0](https://github.com/moovweb/le-deployer/releases/tag/v1.28.0) (2020-12-17)
## What’s Changed* Feat: XDN Console redirects (#568) @adrien-k* Redeploy s3 path fix (#595) @leotoll* chore(Airbrake): clarify or skip some errors (#594) @adrien-k* XDN-6138_Allow-users-to-rename-sites_Markus-Tarn (#557) @MarkusTarn* fix(Docker): fail to start because missing yarn (#592) @adrien-k* Store s3 download path in db (#591) @leotoll---
## [v1.27.4](https://github.com/moovweb/le-deployer/releases/tag/v1.27.4) (2020-12-14)
## What’s Changed* Added latest label to build overview page (#580) @dijs* Ignore no session error (#577) @dijs* feat(MetricsService) Catch all status x >= 400 and ECONNREFUSED and s… (#564) @KaarelKelk* Fix for XDN-7573 relabel criteria button (#589) @ianand* fix(Rubocop) exclude mocks and fix errors (#590) @KaarelKelk* Fix integration tests (#588) @leotoll---