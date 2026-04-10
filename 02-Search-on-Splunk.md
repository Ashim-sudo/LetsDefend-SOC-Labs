# 02 - Search on Splunk (Let's Defend)

## What I Learned
- How to perform basic and advanced searches in Splunk
- Using SPL (Search Processing Language) commands effectively
- Filtering data using index, sourcetype, host, and time range
- Common commands: stats, table, sort, head, tail, dedup
- Creating meaningful searches for security events

## Key Takeaways
- Splunk Search is the foundation for investigation and analysis in SOC
- Learned how to write efficient SPL queries to find specific security events quickly
- Understood the importance of proper field selection and time range

## Most Useful SPL Commands Learned
- `index=main sourcetype=access_combined`
- `| stats count by status`
- `| table _time, src_ip, action, status`
- `| sort -count`
- `| dedup src_ip`

## Concepts Covered
- SPL (Search Processing Language)
- Search Filters and Fields
- Aggregation using stats
- Data Visualization Basics

---
