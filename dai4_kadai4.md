```uml
@startuml
start
:weather=0;

if(weather==0) then (true)
:快晴です;
else if(weather==1) then (true)
:曇りです;
else if(weather==2) then (true)
:雨です;
else (false)
:不明です;
endif

end
@enduml
```
