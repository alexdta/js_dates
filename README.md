# js_dates
Comparing Start and End Dates from input[type=date] values

Start date must always be less than end date at least by one day

Days are added or subtracted using milliseconds (1 day = 86400000)

Two ways to set the value
1) input.value = resultDate.toISOString().substring(0, 10)
2) input.valueAsDate = resultDate
