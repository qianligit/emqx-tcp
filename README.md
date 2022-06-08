# emqx-tcp
emqx private tcp protocol connector

## 1. 预连接

终端：68 1E 00 81 05 84 00 00 00 00 00 00 6C C0 01 00 00 00 3C 07 E4 08 06 04 10 2C 0E 00 00 7A 06 16

```json
{"APDU":{"PiidAcd":{"ServiceNum":0,"ReqACD":0,"ServicePriority":0},"RequestType":0,"HeartBeatCycle":60,"RequestTime":{"Year":2020,"Month":8,"DayOfMonth":6,"DayOfWeek":4,"Hour":16,"Minute":44,"Second":14,"Milliseconds":0},"TimeTagOpt":122,"DateTimes":{"Year":{"Value":0},"Month":0,"Day":0,"Hour":0,"Minute":0,"Second":0},"Ti":{"Einheit":0,"TimeInterval":{"Value":0}}},"Len":30,"Ctl":129,"Dir":1,"Prm":0,"FrameFlag":0,"Fn":1,"SAFlag":0,"AddrType":0,"LogicAddr":0,"AddrLen":6,"SAddr":"hAAAAAAA","CAddr":0,"ApduFlag":0,"MsgTime":"2020-08-22T10:03:11.8762172+08:00"}
```
