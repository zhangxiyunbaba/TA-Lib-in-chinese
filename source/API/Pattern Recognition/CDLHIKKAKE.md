# CDLHIKKAKE
中文名字：陷阱线
用法：第二日K线在第一日K线之内，即第二日最高价低于第一日的最高价，最低价高于第一日的最低价，第三日K线 高于前2日高点和低于前2日低点（在上升趋势中，形成向上突破陷阱），或者低于前两日高点和低于前两日高点（在下降趋势中，形成向下突破陷阱）。
确认：随后三日K线会形成确认是否是陷阱，某一天的收盘价高于第二根K线的最高点或者低于第二根K线的最低点。
调用方法：interget = talib. CDLHIKKAKE (open, high, low, close)
输出： 看涨行情中返回正数（1到100），看跌行情中返回负数（-1 到 -100）。 
