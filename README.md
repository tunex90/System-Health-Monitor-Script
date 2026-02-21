# System-Health-Monitor-Script
This is a monitoring script that checks: * Disk usage * Memory usage * CPU load
System Health Monitor Script

Objective: Create a monitoring script that checks:

* Disk usage
* Memory usage
* CPU load



Requirements: 

1. If disk usage > 80%:

   * Print warning

2. If memory usage > 75%:

   * Print warning

3. Output must include:

   * Current date
   * System hostname

4. Append results to `health.log`

5. Schedule with cron every 5 minutes



Skills Tested: 

* Command substitution `$( )`
* `df`, `free`, `uptime`
* `awk`
* Arithmetic comparisons
* Variables

