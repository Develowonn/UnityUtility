# UNITY UTILITY LIST

## 🧩 Singleton.cs

Unity에서 자주 사용하는 **MonoBehaviour 싱글톤 패턴**을 간편하게 적용할 수 있는 유틸리티 스크립트입니다.

### ✨ 사용 예시

```csharp
public class GameManager : Singleton<GameManager>
{
    protected override void Awake()
    {
        base.Awake();
        // 초기화 코드 작성
    }
}
