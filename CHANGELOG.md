## v0.4.3

- Add operator Echo [#65](https://github.com/cookpad/kuroko2/pull/65)
- Notify expected_time warnings from the root task only [#66](https://github.com/cookpad/kuroko2/pull/66)
- Add execution_id to process_signals table and use it [#67](https://github.com/cookpad/kuroko2/pull/67)
- Following rails5.1.2 ActiveSupport::Duration changes [#69](https://github.com/cookpad/kuroko2/pull/69)
- Send SIGTERM only once on timeout  [#72](https://github.com/cookpad/kuroko2/pull/72)
- Load extension modules from top-level [#75](https://github.com/cookpad/kuroko2/pull/75)
- Resolve next scheduling ploblems  [#76](https://github.com/cookpad/kuroko2/pull/76)
- Set process title of command-executor from its command [#77](https://github.com/cookpad/kuroko2/pull/77)
- Fix icon font displaying bug [#78](https://github.com/cookpad/kuroko2/pull/78)
- Fix deprecated #delete_all conditions parameter [#80](https://github.com/cookpad/kuroko2/pull/80)
- Set default rails port number to align `kuroko2.yml` url settings [#82](https://github.com/cookpad/kuroko2/pull/82)
- Add retry task [#83](https://github.com/cookpad/kuroko2/pull/83)
- Fix google_oauth2 hd check: fix hd option fetching [#84](https://github.com/cookpad/kuroko2/pull/84)
- Fix hipChat notifier [#88](https://github.com/cookpad/kuroko2/pull/88)

## v0.4.2

- Use commonmarker gem [#63](https://github.com/cookpad/kuroko2/pull/63)
- Fix not executing multiple fork tasks [#64](https://github.com/cookpad/kuroko2/pull/64)

## v0.4.1

- Fix schema.rb  [#58](https://github.com/cookpad/kuroko2/pull/58)
- Fix typo: registory to registry [#60](https://github.com/cookpad/kuroko2/pull/60)
- Fix length validation for slack_channel column to adapt # symbol [#61](https://github.com/cookpad/kuroko2/pull/61)

## v0.4.0

- Fix login failure [#43](https://github.com/cookpad/kuroko2/pull/43)
- Order job instance logs returned by XHR [#44](https://github.com/cookpad/kuroko2/pull/44)
- To selectable administrators field [#45](https://github.com/cookpad/kuroko2/pull/45)
- Render instance logs by JavaScript to fix flicker [#46](https://github.com/cookpad/kuroko2/pull/46)
- Add `parallel_fork` task [#47](https://github.com/cookpad/kuroko2/pull/47)
- Avoid nil errors in API authentication [#52](https://github.com/cookpad/kuroko2/pull/52)
- Fix job not being recorded as completed when exit status > 127 [#55](https://github.com/cookpad/kuroko2/pull/55)
- Support Rails5.1.0 [#56](https://github.com/cookpad/kuroko2/pull/56)

## v0.3.4

- Kill n+1 queries [#41](https://github.com/cookpad/kuroko2/pull/41)

## v0.3.3

- Allow user to receive notification [#39](https://github.com/cookpad/kuroko2/pull/39)

## v0.3.2

- Change kuroko script formatter to rails helper and expand definition name if needed [#37](https://github.com/cookpad/kuroko2/pull/37)
- To simplify slack messages [#36](https://github.com/cookpad/kuroko2/pull/36)
- Link to docs/index.md [#35](https://github.com/cookpad/kuroko2/pull/35)
- Refactor configurations [#34](https://github.com/cookpad/kuroko2/pull/34)
- Make use content_for method [#33](https://github.com/cookpad/kuroko2/pull/33)
- Kill n+1 queries [#32](https://github.com/cookpad/kuroko2/pull/32)
- Add foreman to development dependency gem list [#30](https://github.com/cookpad/kuroko2/pull/30)
- Add confirmation dialog when to cancel failed job instance [#29](https://github.com/cookpad/kuroko2/pull/29)

## v0.3.1

- Do not include `job_instances` [#28](https://github.com/cookpad/kuroko2/pull/28)

## v0.3.0

- To skippable waiting tokens [#27](https://github.com/cookpad/kuroko2/pull/27)
- Remove mysql2 from runtime dependency [#26](https://github.com/cookpad/kuroko2/pull/26)
- Job instance logs should be ordered [#25](https://github.com/cookpad/kuroko2/pull/25)
- Kill n+1 queries and fix tag links [#22](https://github.com/cookpad/kuroko2/pull/22)
- Display tags [#21](https://github.com/cookpad/kuroko2/pull/21)
- Support webhook notification [#16](https://github.com/cookpad/kuroko2/pull/16)
- Display seconds in Logs/Execution Logs timestamp [#18](https://github.com/cookpad/kuroko2/pull/18)
- Always define end_time for job limelines [#17](https://github.com/cookpad/kuroko2/pull/17)
- Fix sub_process task linker [#15](https://github.com/cookpad/kuroko2/pull/15)
- Change `Notify success event to Slack/Hipchat` option to `Notify all event to Slack/Hipchat` [#8](https://github.com/cookpad/kuroko2/pull/8) [#19](https://github.com/cookpad/kuroko2/pull/19)
- Add example systemd unit files [#14](https://github.com/cookpad/kuroko2/pull/14)
- Convert scheduled times into AS::TimeWithZone [#13](https://github.com/cookpad/kuroko2/pull/13)
- Fix queue validation [#12](https://github.com/cookpad/kuroko2/pull/12)
- Add users_controller#edit [#9](https://github.com/cookpad/kuroko2/pull/9)

## v0.2.3
- Fix Kuroko2::JobDefinition.search_by [#11](https://github.com/cookpad/kuroko2/pull/11)
- Validate hd parameter if configured [#10](https://github.com/cookpad/kuroko2/pull/10)

## v0.2.2
- s/Time.now/Time.current/ [#4](https://github.com/cookpad/kuroko2/pull/4)
- Splitting the autoload directory [#5](https://github.com/cookpad/kuroko2/pull/5)
- Add documentations [#6](https://github.com/cookpad/kuroko2/pull/6)
- Fix loading Kuroko2.logger [#7](https://github.com/cookpad/kuroko2/pull/7)

## v0.2.1
- Eager load kuroko2 lib directory [#2](https://github.com/cookpad/kuroko2/pull/2)
- Use utf8mb4 as default in database.yml [#3](https://github.com/cookpad/kuroko2/pull/3)

## v0.2.0
- Initial OSS version
