# Vector
## Distance
- Latex
    - Alpha : $\alpha$
- 벡터의 거리는 피타코라스 정의로 표현될 수 있음
    - ${a^2+b^2}=c^2
    - $\sqrt{a^2+b^2}=c$
- 2차 방정식의 해 : 근의 공식
    - $\frac{-b \pm \sqrt{b^2-4ac}}{2a}$
- 코드 블럭
 ```c#
 private static void GetDirectory(string path)
        {
            string[] directories = Directory.GetDirectories(path);

            foreach (string d in directories)
            {
                Console.WriteLine(d);

                GetDirectory(d);
            }                
        }
```

- 테이블
Test|Test2|Test3
---|---|---
c#|c++|python
Unity|Unreal|Godot
meta|uasset|gasset

---
