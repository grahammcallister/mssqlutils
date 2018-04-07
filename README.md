# mssqlutils
Useful MS Sql snippets


# WHERE

## Last 15 minutes
[DateColumnName] > DATEADD(MINUTE, -15, GETDATE())

## Last Hour
[DateColumnName] > DATEADD(HOUR, -1, GETDATE())

## Last Day
[DateColumnName] > DATEADD(DAY, -1, GETDATE())
