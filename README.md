# Calendar-conversion
阴阳历日期转换
## api
#### 日期格式转换（"2006-01-02"）
+ func SolarDateToLunarDate(string) string
+ func LunarDateToSolarDate(string) string
#### 标准时间戳转换
+ func LunarTimeToSolarTime(time.Time) time.Time
+ func SolarTimeToLunarTime(time.Time) time.Time 
#### 自定义数据结构Lunar与Solar转换
+ func SolarToLunar(Solar) *Lunar
+ func LunarToSolar(Lunar) *Solar
#### 查询生日重合的年份
+ func FindYear(birthday string) []int
