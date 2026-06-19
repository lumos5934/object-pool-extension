# Object Pool Extensions
유니티 오브젝트 풀을 상속하여 여러 풀을 제공합니다.

<br>
<br>
<br>


#### Tracked Pool
풀에서 꺼낸 객체를 `HashSet` 으로 관리하여 `ReleaseAll()`을 실행 할 수 있습니다.

```cs

var trackedPool = new TrackedPool();
trackedPool.ReleaseAll();

```
