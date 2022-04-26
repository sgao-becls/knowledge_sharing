- [ ] 查看垃圾回收
```
ObjectSpace.count_objects[:T_OBJECT]
ObjectSpace.count_objects[:T_CLASS]
100.times {'hello'}
200.times {Class.new}
ObjectSpace.count_objects[:T_OBJECT]
ObjectSpace.count_objects[:T_CLASS]
GC.start
ObjectSpace.count_objects[:T_OBJECT]
ObjectSpace.count_objects[:T_CLASS]
```

- [ ] 第一个类

class Radio

    def initialize(volume)
        @volume = volume
    end

end

