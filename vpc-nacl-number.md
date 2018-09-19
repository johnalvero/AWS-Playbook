For easy identification of rules, the following number scheme is recommended

|Number Series|Description|Example|
|-------------|-----------|-------|
|1XX|Makes VPC/Network work|NTP, DNS, HTTP Proxy, Inter-subnet traffic,Ephemeral Ports|
|2XX|Makes the application work|HTTP, HTTPS|
|3XX|Does not affect production traffic|Nagios,Ops tools|
|4XX|Administrative consoles|Sophos port 4444|
|10xxx|Testing rules. Can be removed without notice||
