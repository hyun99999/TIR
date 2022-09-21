***🔗 Today I Read and Reviewed***
> 하루에. 한 개씩. 기업들의 개발 블로그를 읽고, 느낀 점을 짧게 기록하기 대작전

<br>

<div align=center>

<img src="https://user-images.githubusercontent.com/69136340/168649639-4398fa57-4ea6-450d-ac81-b3c16492ef92.gif" width ="250">

</div>

 <div align = center>

 ## Kakao Tech [🔗](https://tech.kakao.com)

 </div>

- [x] `05/17` [카카오엔터프라이즈가 GitHub Actions를 사용하는 이유](https://tech.kakao.com/2022/05/06/github-actions/)
- [x] `05/17` [효과적인 코드리뷰를 위한 리뷰어의 자세](https://tech.kakao.com/2022/03/17/2022-newkrew-onboarding-codereview/)
    > - _느낀점_ : 읽고 나니 코드리뷰의 어투, 방향, 중점사항, 템플릿 등 많은 부분에서 비슷하게 노력하고 있었다. 현업에서는 어떻게 진행할까? 우리가 지금 코드리뷰를 잘 하고 있는걸까? 하고 궁금하고, 불안했던 것이 어느정도 채워진 기분이었다. 주니어 레벨에서의 코드리뷰는 크게 차이나지 않는다는 이야기를 얼핏들었지만 그 중에서도 현명하게 진행하고 싶었다. 그 부분이 조금은 통했던 것 같다. 더욱 현업의 개발 문화가 궁금해졌다.
- [x] `05/18` [2022 신입 공채 iOS 기술 온보딩을 소개합니다.](https://tech.kakao.com/2022/03/16/2022-newkrew-onboarding-ios/)
    > - _느낀점_ : 신입 iOS 개발자의 온보딩과 그 속에서의 느낀점을 읽다보니 나도 경험해보고 싶다는 생각을 했다. 현업자분들의 코드리뷰와 개발 문화, 기업의 어떠한 일들이 궁금해졌다. 점점 궁금증이 많아지는듯.. 하지만? 오히려 얼른 알고 싶다는 동기부여가 되었다. 내가 신입 개발자로 입사하게 된다면 겪을 온보딩이기 때문에 아~ 이런걸 하는거구나 라고 느꼈다. 카카오에는 5가지 문화가 있다고 한다. `나보다 동료의 생각이 더 옳을 수 있다는 믿음을 가지는 것` 이 그 중 하나이다. 내가 되고 싶은 동료이자 희망하는 동료의 가치관은 이러하다. `등을 맞대고 서로의 코드를 믿고 존중할 수 있는 동료` 이다. 이러한 가치관이 카카오라는 대기업의 문화에 대해서 알고나니 좀 더 확신을 가지게 되었다.
 
- [X] `05/18` [[Ka-reer Up!] 글을 읽고 쓰는 경험을 제공하는 창작자앱개발파트 이야기](https://tech.kakao.com/2022/03/21/client-recruitment-01/)
    > - _느낀점_ : 창작자앱 개발 파트는 브런치와 티스토리를 개발하고 있었다. OS 에 구분되지 않게 소통하고 다양한 주제를 가지고 스터디하고 함께 논의한다는 점이 굉장히 멋졌다. _앱잼에서 안드분들과 함께 해당 문제에 대해서 고민하고 논의할 때, 다른 OS 플랫폼에 대해서 알 수 있어서 흥미로웠고, 같은 기능에 대해서 서로가 필요로 하는 리소스가 다르기 때문에 이 부분을 조율하는데 성장을 겪었다._ 이러하기 때문에 팀문화가 굉장히 끌렸다. 또한, 담당자를 고정하지 않고 돌아가며 유연하게 대응하기 때문에 서비스의 이해와 오너십을 유지할 수 있다는 점 또한 내 가치관과 매우 맞았다. 원할하게 대응할 수 있고, 코드리뷰 뿐만 아니라 이러한 문화가 오너십을 유지할 수 있다는 점에도 동의한다.
- [x] `7/5` [Swift Package Manager 적용기](https://tech.kakao.com/2022/06/02/swift-package-manager/)
    > - _느낀점_ : Apple 의 퍼스트 파티인 Swift Package Manager 를 카페앱에 도입한 경험에 대한 글을 읽었다. 써드 파티인 CocoaPods 을 주요로 사용하지만 왜 SPM 을 도입하게 되었는지에 대해 읽는 것이 포인트가 되지 않을까 싶다. 첫 번째 도입 배경은 빌드 속도 등 여러가지 개선을 위한 모듈화였다. 두 번째는 Dependency 관리였다. 세 번째는 애플의 공식 도구이므로 계속된 발전이 있을 종속성 도구이기 때문이다. 네 번째는 기술 제한이 없었기에 도입 도전이었다고 한다. 분명히 SPM 을 사용하는 장점들임에 분명했다. 그리고 다음 읽는 포인트로 도입과정에 느낀점이 궁금했다. 우선 패키지의 구성 요소에는 targets, products, dependencies 크게 3가지로 이루어져 있다고 한다. Swift Package Manager 의 내부 빌드 과정에 대해서도 읽을 수 있었다. Apple 의 공식 c 컴파일러인 Clang 을 통해서 프레임워크의 헤더를 찾아 파싱 후 캐싱기능을 제공하여 빌드 시간을 개선하는 역할을 한다고 하고, MyTarget-Swift.h 파일을 통해서 Objective-C 에서도 Swift 로 작성된 코드를 사용할 수 있는 인터페이스 역할을 한다고 한다. 이래서 Swift 로 작성한 패키지도 Objective-C 에서 사용할 수 있구나 라고 알았다. swiftmodule 파일을 통해서 모듈에 선언된 API 를 다른 모듈에 노출시키는 역할을 한다고 한다. 또한, 모듈의 리소스 번들에 접근할 때 `Bundle.module` 이라는 accessor 로 접근하게 되는데 Foundation.Bundle 에 module 이라는 static 변수가 있고 각 bundleName 이 지정되어 있기 떄문에 위의 accessor 로 접근할 수 있음을 알 수 있었다. 아직 어려운 개념들이 많았지만 얼핏 이렇게라도 어떤 것들의 역할들로 왜 패키지를 사용할 수 있는지 알게되어서 재밌었다. 빌드가 됨에서 끝나는 것이 아니라 어떤 과정을 통해서 빌드가 되는지에 대해 아는것도 중요하다고 느꼈다. 마지막으로 이슈와 해결 사례도 적어주셨는데 정말 감사드렸다. ㅎㅎ Keditor SDK 업무를 진행하며 SPM 을 도입하면서 겪었던 이슈에 대해서 소개해주셨다. SPM 의 특징 중 하나는 C계열과 Swift 파일을 하나의 타겟으로 사용하지 못한다는 점이었다. 이것 역시 내가 이전에 읽었던 SPM 의 단점이었는데 어떻게 해결하셨을까 궁금했다. 바로 타겟을 분리하여 dependency 로 해결하셨다고 한다. 설명은 간단하지만 이렇게 돌파하시는구나 라고 생각이 들었다. 카페앱에서도 이슈가 있으셨는데Cocoapods 와 SPM 을 동시에 적용하다보니까 각각의 종속성 도구에 동일한 라이브러리를 추가하지 않을 수 있었지만, 추가된 라이브러리의 dependency 로 동일한 라이브러리를 가지고 있는 상황에서는 static linking 이라면 컴파일 에러, dynamic linking 이라면 런타임 워닝이 발생했다고 한다. 그래서 이를 해결하기 위해서 해당 파트의 SDK 는 작업을 하시고, opensource 는 fork 한 후 작업하시고 협조가 되는 enterprise library 는 지원 요청을 하셨다고 한다. 추후에 CocoaPods 를 제거하여 하나의 종속성 도구로써 SPM 을 사용하신다고 하셨다. 이슈 해결과정까지 아주 값진 글을 읽게 된 것 같다. 

<div align = center>
 
## KakaoEnterprise[🔗]((https://tech.kakaoenterprise.com))

</div>

- [x] `06/17` [시니어 개발자의 카카오엔터프라이즈 500일의 기록](https://tech.kakaoenterprise.com/131?category=882489)
    > - _느낀점_ : 카카오엔터프라이즈는 카카오의 자회사 중 B2B 를 전문으로 하는 곳이다. 대표적으로 카카오 워크가 생각이 났다. 카카오엔터프라이즈는 수평적인 피드백을 위한 영어 호칭, 아지트를 사용하여 투명한 정보 공유, 카카오워크를 사용한 커뮤니케이션을 작성자분이 강조했다. 크루의 법인카드 사용 내역까지 아지트를 통해서 공개된다니 이를 비롯해서 사내 업무 진행 상황을 확인가능하다고 한다. 대신 100:0 원칙을 지켜야한다고 한다. 공개된 모든(100) 정보는 절대 유출하지 않는다(0) 을 의미한다고 한다. 투명함과 공유에 대한 책임감을 강조하는 것을 느꼈다.
수평적인 문화에 대한 글을 읽으면 신기했다. 원한다면 사내의 어떤 회의라도 참석할 수 있다는 것이다. 정말 아무 회의나 들어가서 자기소개를 하고 참관을 하면 된다고 한다. 또한 양심과 상식적인 선에서 법인카들르 활용한 상한선이 존재하지 않는다고 하니 상상 속의 회사보다 굉장히 직원들을 믿는 모습들이 느껴졌다.
이러한 문화들을 건강하게 유지해 나갈 수만 있다면 정말 대단한 기업 문화라는 생각이 들었다. 
작성자분은 20년 스타트업 경력이 있으시다고 했다. 그래서 우리나라 B2B 회사들은 고객의 요구사항을 그대로 솔루션 요구사항에 적용하는 것만으로도 매우 바쁘기 때문에 개발자들 스스로가 생각해서 계획하는 문화가 부족하다고 언급하셨다. 즉, 고객들이 원하기 때문에 라는 것이 반영이 많이 된다는 것이죠. 하지만 카카오엔터프라이즈는 개발자들이 기획에 매우 적극적으로 참여한다고 한다. 이러한 흐름이 B2B 시장에서 새로운 물결을 일으킬 수 있다고 한다. B2B 시장에서의 카카오엔터프라이즈와 이런 개발자 중심 문화가 궁금해졌다.
- [x] `6/18` [신입 개발자 공채 입사 후, 우리는 이렇게 살고 있어!](https://tech.kakaoenterprise.com/114?category=882489)
    > - _느낀점_ : 카카오엔터프라이즈는 대기업의 탄탄한 기반의 장점과 스타트업의 도전정신 장점을 갖춘 회사라고 한다. 우아한형제들 글을 읽을 때도 느꼈지만 이러한 두가지 장점이 결합된 곳에서는 모두가 창업자 정신을 가질 수 있고, 안정적인 환경이 얼마나 도전적인 생각을 이끌어낼 수 있는지 또다시 생가하게 되었다. 공유하고 도와주고 으쌰으쌰할 수 있는 분위기가 느껴졌다. 복지에 대해서도 굉장히 유명했다. 아직은 신입의 입장이지만 점점 연차가 쌓일 수록 이부분도 굉장히 중요해 보인다. 크루들끼리의 자체 스터디와 사내외 교육이 많다는 것도 장점이었다. 회사에 나와서 일만하지 않고 또 그런 인연들이 끊기지 않고, 나의 성장에도 도움이 된다니 굉장히 지향하는 문화였다. 일을 마친 시간에도 자기 개발과 흥미, 취미를 위해서 쏟는 시간들이 회사 업무와도 연결되어 나의 커리어에 도움이 된다는 것은 개발자의 매력이 아닐까 싶다.

 <div align = center>

 ## GMarket Tech [🔗](https://product.gmarket.com/stories/)

 </div>

- [x] `05/19` [디자이너-개발자를 위한 도구, G마켓 디자인 시스템 ‘GDS’](https://product.gmarket.com/2021-03-gds/)
    > - _느낀점_ : SOPT 에서 3주간의 긴 해커톤을 거친 몇개의 프로젝트에서는 디자인 시스템을 구축하는 소식은 들었다. 그러면서 되게 개발하기 안정적이고, 현업하기 편하겠다! 라고 막연히 생각했는데 G마켓의 글을 읽어볼 기회가 생겼다. 역시나 글의 서두에서 말하듯이 디자인 시스템을 구축하는 것은 유지 및 보수에서 효율성을 높이고 있다고 한다. 읽은 후, 끌렸던 장점이자 정의는 디자이너와 개발자 간 동기화된 공통 컴퍼넌트 라는 점입니다. 그동안 프로덕트에 적용된 UI 스크린샷을 찍고 분류를 통해서 컬러와 버튼을 취합하는 등 패턴을 취합하는 UI 인벤토리라는 과정도 흥미로웠습니다. 낯선 용어와 프로세스도 많았지만 눈에 익히고 머리에 한번 담아본다는 생각으로 나중에 도움이 될 것 같습니다. 개발자가 해당 컴포넌트의 스타일의 근거를 인지하고 개발이 가능하다는 것이 장점으로 다가왔습니다.

 <div align = center>

## Brunch [🔗](https://brunch.co.kr/magazine/brunch-dev)
 
</div>

- [x] `05/21` [당신은 어떤 사람과 일하고 싶은가요? - 길고 긴 짝꿍 찾기](https://brunch.co.kr/@babosamo/85)
    > - _느낀점_ : 짝꿍이라는 단어가 끌려서 읽게 되었다. 정말 짝꿍을 잘 만나는 것도. 잘 고르는 것도. 좋은 짝꿍이 되는 것도. 모두가 어려운 것 같다. 그리고 아주 운이 좋아야 가능한 것 같다. 철학이라는 단어를 굉장히 문과적이라고 생각해왔는데 최근 프로젝트가 마무리되면서 어떤 장인이 영혼까지 갈아서 만든다는 표현처럼 정말 내 개발적 철학뿐만 아니라 서비스적인 철학에 대해서 구축하고 쏟아부은 결정체의 느낌이 들었다. 그제야 비로서 나라는 구성원이 그 앱을 통해서 보이고, 같은 철학을 가진 사람들의 목소리들이 보이는 듯하는 생각이 들었다. 브런치의 경우는 해당 글에서 형성된 철학에 최대한 어울리는 개발자를 찾는 부분을 서술했다. 예를 들어 글을 쓰는 습관에 좀 더 어울리는 개발자들을 찾고 있었다. 이러한 글을 보면서 왜 대기업에서도 이직을 하는구나 싶은 생각이 들었다. 아무리 대기업이라도 내가 추구하는 철학, 팀 문화가 맞지 않을 수 있다는 생각이 들었다.
- [x] `5/26` [2021년 9월, iOS 개발자들의 이야기 (1)](https://brunch.co.kr/@eunjin3786/223)
    > - _느낀점_ : 브런치의 iOS 개발자이야기에 대해서 접할 수 있었다. 예전에 소프트웨어공학때 사용했던 여러 use case 와 다이어그램을 작성할때 사용했던 draw.io diagram 에 대해서 사용하시고 있었다. 페어 프로그래밍에 대한 경험도 적혀있었는데 코드에 대한 애착이 생기고 오너쉽이 생긴다고 한다. 그리고 저자는 iOS 에서 페어프로그래밍이 깃헙 diff 만 봐서는 어려웠던 xib, 여러 이미지 에셋들, 다크모드에 대한 컬러 에셋들에 대해서 함께 볼 수 있다는 점이 용이하다고 꼽았다. 21년 10월의 안드파트는 페어프로그래밍을 진행한다고 했는데 iOS 파트도 해보고 싶다고 합니다. 현재 정착이 됐는지도 궁금해졌다. 페어프로그래밍에 대해서 장난삼아 진행했던 적이있는데 확실히 좋았던 점은 내 코드를 누군가와 함께 보면서 논의하고, 컨밴션에 대해서 철저하게 지킬 수 있다는 점이었다. 또한, 동료가 작성하는 코드를 보고만 보면서 생각과 말만하니까 손으로 작성하고 싶은 욕구도 들어서 일에 대한 욕구도 생길 수 있었다. 비록 당시에는 시간을 정해두고 진행하거나 하지 않았기 때문에 페어프로그래밍의 경험에 대해서 좀 더 찾아보고 적용할 수 있는 기회가 생기면 좋겠다고 느꼈다.
- [x] `5/27` [2021년 9월, iOS 개발자들의 이야기 (2)](https://brunch.co.kr/@woongss/1)
    > - _느낀점_ : 21년 카카오 인턴십 과정을 거쳐서 브런치 iOS 개발자로 합류한 분의 글을 읽었다. 인턴생활을 시작하며 클린코드, 클린 아키텍처 책도 선물받고 여러 카카오 선물들도 받았다고 한다. 몇 일전 사비로 구입한 책이기 때문에 되게 부러웠다. 인턴 기간 동안 브런치의 특정 화면에 기능을 추가해서 만드는 토이 프로젝트를 진행했다고 한다. 현업자들의 PR 코드리뷰를 받았다고 하니 나도 뭔가…. 시니어 개발자분들의 코드리뷰를 받고 싶다는 생각이 들었다. 네이밍이나 파라미터의 위치 갯수 사용법 등등 주석 등등 좀 더 좋은 코드에 대해서 고민하는 요즘이고, 현업자분들의 로직에 대해서도 궁금하기 때문이다. 두번째는 브런치 작가와 카카오톡을 연결해주는 기능을 개발하는 실제 프로젝트에 참여했다고 한다. 인턴이지만 UI 와 API 연동에 대한 경험을 했다니 정말 부러울 수가 없었다. 또한, 브런치라는 팀은 라이트닝 토크라는 문화가 있다고 한다. 가볍게 기술에 대해서 특정 토픽에 대해서 여러사람들과 생각을 말하고 듣는 것이 참 좋아보였다.
- [x] `6/25` [Large Scale 앱을 생산성 높게 개발한다고요?](https://brunch.co.kr/@eunjin3786/226)
    > - _느낀점_ : 에어비엔비 팀이 Large-Scale iOS 앱을 개발하면서 겪은 어려움과 솔류션에 대한 이야기를 요약한 글을 읽었다. 
코드에 계층 구조가 없어서 찾기 어려운 것이 첫 번째 문제였다. large codebase 로 Xcode 를 여는 시간도 1-2분이 걸리고 긴 빌드 시간에 심지어 외부 모니터 플러그를 뽑아서 컴파일을 하기까지 했다고 한다. 이러한 느린 코드베이스 속도가 두 번째 문제였다. 이를 해결하기 위해서 에어비엔비는 세가지 솔루션을 구현했다고 한다.첫 번째는 Facebook 의 Buck 빌드 시스템을 채택하여 빌드 속도를 향샹 시켰다. 두 번째는 계층구조 문제를 해결하기 위해서 organizational structure 를 디자인했다고 한다. 세 번째는 하나의 모듈과 그 모듈의 의존성에 대한 임시 Xcode workspace 를 만들어 dev apps 를 가능하게 했다. 에어비엔비는 75명의 iOS 엔지니어와 62개의 언어로 앱을 제공할 수준으로 어마어마한 규모를 가지고 있다. 이렇게 큰 프로젝트에서는 큰 만큼 또 다른 이슈사항이 있구나 라고 느꼈다. 빌드 속도가 느리면 정말 개발을 하기 싫을텐데..라고 생각했고, 당연하게도 이러한 문제를 가만히 두고 볼 개발자들이 아니구나라고 생각했다.
- [x] `6/27` [ReactorKit 테스트하기](https://brunch.co.kr/@d2e0f07c7ddb454/1)
    > - _느낀점_: 브런치 iOS 앱은 ReactorKit 을 사용한다고 공고 등에서 봤었는데 ReactorKit 을 테스트하는 글을 일게 되었다. 테스트 할때는 RxTest 와 RxExpect 를 사용한다고 한다. 둘다 사용해보지 않았지만 흐름만 읽어보자는 생각을 했다. ReactorKit 은 단방향으로 사용자의 액션을 받아서 비지니스 로직을 수행한 후 상태를 변경한다. 뷰에서는 유저의 인터렉션으로 적절한 액션이 리액터에 전달되었는지, 상태 변화에 따라 뷰의 프로퍼티가 제대로 설정되는지, 액션이 발생했을 때 비즈니스 로직의 결과로 상태가 적절하게 바뀌었는지 리액터에서 테스트가 정리된 글이다. 확실히 테스트를 하게되면 제대로 맞게되었는지 확인할 항목들이었다. 액션에 대한 여러번의 상태 변경 사항이 있을때 RxTest 로 작성한 코드를 RxExpect 로 변경하는 과정을 읽을 수 있었다. 글쓴이님도 테스트 코드를 작성하는데 익숙하지 않아 공부중이시라고 하시는데 최근 공고나 글을 읽으면서 더 큰 프로젝트를 위해 필요성을 가지고 공부할 필요가 있을 것 같다.
- [x] `7/2` [당신은 시니어인가요?](https://brunch.co.kr/@woongss/6)
    > - _느낀점_: 브런치의 iOS 개발자분이 작성하신 글이었다. 제목부터 매우 자극적이었다. ㅎㅎ 첫대목의 질문은 언제부터 주니어가 아니라고 할 수 있을까요? 였다. 맞다. 사실은 주니어가 아니어야 시니어가 되니 말이다. 각자만의 대답에 대해서 정리해서 작성해주셨다. 이러한 주제에 대해서 다른 사람과 함께 이야기하고 토론하는 것은 매우 흥미로워 보인다. 나도 cs 스터디에서 어떤 가치관이네 면접 질문에 대해서 가끔 이야기하곤 하는데 끝나고 가끔 정리된 글을 보면 각자 많은 다른 생각과 가치관을 가지고 있고 항상 겸손하며 배우는 자세가 필요하다고 느낀다. 현업자분들이 생각하는 주니어를 벗는 것은  아니라 선택의 상황에서 판단을 내릴 수 있을 때. 3년차 정도. 다른 사람에게 설명해주거나 알려줄 수 있을 때. 다른 분은 5년까지는 주니어 7년 이상은 시니어라고 했다. 시니어는 문화를 만들 수 있는 사람이라는 의견도 있었다. 개발 실력도 실력이지만 어떤 판단과 주변사람들에 대한 영향, 팀에 대한 영향도 중요한 요소인듯 하다. 정작 3년차인 개발자분들의 생각도 작성되었다. 이 부분도 굉장히 흥미로운 관점이라고 느꼈다. 당연한 것 아닌가 남들이 평가하는 연차에서의 자신의 위치를 어떻게 생각할까 궁금했다. 자신이 작성하는 코드에 대해서 뭘 잘못하고 있는지 인지하고 짜는 것이 느껴진다고 한다. 자신에 대한 객관화도 생기는 듯하다. 주니어로서 바라보는 시니어와 시니어가 바라보는 시니어에 대해서 읽을 수 있었던 좋은 글 같다. 글 내용은 가벼운 이야기로 시작했지만 주제는 그렇지 않았다는 글쓴이의 글에 동의하게 되었다.
- [x] `7/3` [카카오 개발자 생활기](https://brunch.co.kr/@d2e0f07c7ddb454/3)
    > - _느낀점_: TIR 을 시작했던 이유로 이런 현업 개발자분들의 회사 내의 문화를 엿보기 위함도 컸다. 오늘은 2021.10월 즘에 입사하신 iOS 개발자님의 글을 읽게 되었다. 항상 웰컴 키트가 처음에 나오게되면 눈이 돌아가는 것 같다. 이런 굿즈나 장비에도 관심이 있는지라 프로젝트를 진행하면 굿즈 발주부터 기다리던 나에게는 정말 동기부여가 되는 요소다. 게더타운을 통해서 온보딩을 진행하셨다고 한다. 요즘은 zep 이라는 것이 또 비대면 미팅에 많이 사용되는 듯 하다. 주니어 개발자들에게 버디가 배치되는 듯하다. 좀 더 팀에 녹아들기 좋을 것 같다. 브런치를 개발하는 팀은 창작자앱 개발파트라고 불린다. 스터디가 있는 경우 따로 모여서 해당 업무를 수행한다고 하니 스터디 역시 하나의 업무처럼 진행되는 모습이 굉장히 자유롭고 함께라는 느낌이 강했다. 데일리 스크럼에 참여하는 것 외에도 WWDC 세션 보기도 있다고 하니… 본인의 성장이 팀의 성장과도 이어짐을 믿고 있는 듯한 느낌을 받았다. 글쓴이님이 뽑은 팀원들의 공통점이 두 개라고 하신다. 기술 공유에 진심이고, 독서를 많이한다는 점이다. 부러운 느낌을 받았다. 팀에 이런 개발 문화가 있다면 같이 고양됨을 느낄 수 있지 않을까 한다. 이러한 신입 개발자분들이 적는 글을 보며 나도 좋은 동료가 되고 싶음을 항상 느끼고 있다. 취업은 10승이 아닌 1승이어도 된다는 글에 동의하는 사람으로서 좋은 기회를 잡기 위해 준비해야할 것 같다.
- [x] `7/8` [개발자의 번아웃 종류와 대처법](https://brunch.co.kr/@eunjin3786/230)
    > - _느낀점_ : iOS 개발자님의 유튜버 드림코딩 엘리님의 영상을 보고 작성한 개발자의 번아웃에 대한 글을 읽었다. 개발자가 되기 위해서는 기술, 협업을 잘하기 위한 소프트 스킬, 리더쉽 스킬 까지도 학습해야한다고 한다. 정말 번아웃이 안올수가 없겠다고 생각했다. ㅎㅎ 그만큼 번아웃에도 다른 대처법을 통해 이겨내야한다고 한다. 육체적인 번아웃이라면 쉬기! 불확실성에서 불안함이 온다면 목표와 비전을 설정하기! 결과가 보이지 않는다면 과정을 즐기기! 이에 대한 자세한 이야기도 있었다. 생각해보면 이런것에 대한 대처법을 정해두지 않았을 때는 고민에 고민을 거치고 여러가지 시도 끝에 결국 그렇게 했던 것 같다. 그 과정들이 모여 목표와 비전에 대해서 생각해보기도 하고 행복회로를 돌리며 과정에 집중하며 과정 속에 살기도 하고 했던 것 같다. 이러한 자신만의 번아웃에 대응하는 요령정도는 가지고 있는 것이 좋겠다고 생각했다.
- [x] `7/14` [Rx에서 Swift Concurrency 사용하기](https://brunch.co.kr/@eunjin3786/254)
    > - _느낀점_ : RxSwift 6.5.0 에서 Swift Concurrency 를 사용할 수 있게 되었고 최근에 RxSwift 공부를 하고 있기 때문에 읽어보면서 알아보려고 한다. RxSwift 공부를 하니 이런 블로그 글도 읽을 수 있다고 생각이 들었다. 끊임없이 공부해야함을 또 다시 느낀다. 이제 async/awiat syntax 를 사용하여 값 또는 에러를 기다릴 수 있었다. observable 를 구독하고 onNext 매개변수 클로저 안에서 사용하지만 Taks 블럭 안에서 do-catch 문안에서 try await 키워드와 함께 사용할 수 있게 되었습니다. 에러를 방출하지 않는 Stream 인 RxCocoa 에서의 Driver 와 Signal 은 에러를 방출하지 않기 때문에 do-catch문 없이 사용할 수 있다. 반대로 Swift Concurrency 의 코드를 Rx 로 변경하는 것도 가능하다. AsyncStream 의 경우 asObservable 로 변경이 가능했다. Rx 에 적용하기에는 아직 기회가 없지만 분명히 도움이 되었던 글이었다.
<div align = center>
 
## NAVER D2[🔗](https://d2.naver.com/search?keyword=ios&sort=postPublishedAt%2Cdesc)

</div>

- [x] `6/9` [2022 OPEN CLASS 다시보기](https://tv.naver.com/v/27083539)
    > - _느낀점_ : 네이버에서의 Career Talk 과 최근에 시작한 채용전형인 Track 인턴십과 공채 대해서 소개해주는 영상을 보았다. 인턴십과 공채 두개 모두를 고민하고 있었고, 네이버에서 개발자의 삶이 궁금해서 시청하게 되었다. 인턴십은 내가 원하는 분야의 특정 부서에 지원 할 수 있고, 빠르게 해당 부서의 문화를 겪어볼 수 있는 점이 장점이라고 한다. 공채는 탄탄한 온보딩 과정을 거칠 수 있고, 개발외적으로 지원하는 많은 기술에 대해서 배움이 가능한 것이 장점이라고 한다. 또한, 온보딩 후에는 네이버 계열을 선택할 수 있다고 하니 좋은 점 같다. 
    > 
    > 다양한 기술조직들이 존재하기때문에 제 2사옥인 1784 프로젝트(사람과 로봇이 공존하는 사회)와 같은 것도 가능하다라고 느꼈다. 해당 프로젝트는 신기술을 우리가 직접 사용해보고 적용된 공간을 이용함으로써 출시할 수 있고 글로벌로 나갈 수 있는 장점이 있다고 한다. 되게 신기한 프로젝트라고 느꼈다.

<div align = center>
 
## 우아한 형제들[🔗](https://techblog.woowahan.com)
 
</div>

- [x] `5/29` [우아한 소개&인터뷰](https://career.woowahan.com/woowa-team)
    > - _느낀점_ : - 서빙로봇사업팀
우아한형제들이랑는 회사내의 작은 ‘스타트업’ 과 같은 분위기로 일하고 있다는 소개가 인상적이었다. 우아한형제들이라는 성공한 기업내에서 스타트업과 같은 문화가 살아 숨쉰다는 것만으로도 회사에 새로운 숨결같았다. 그렇기에 회사원보다는 창업멤버같은 마인드로 일하신다고 한다. 서빙로봇을 몇몇 매장에서 경험해본적이 있는데 생각보다 굉장히 귀여웠고(뭔가 테이블을 찾아가며 으쌰으쌰하는 이미지였다) 일반 종업원들이 다른 업무에 집중할 수 있어보였고, 테이블에서는 태블릿을 통해서 주문해서 굉장히 편했던 기억이 있다.
    > - 딜리버리플랫폼팀
    > 주문 전후로 고객에게 배달이 될 때 필요한 모든 일을 담당한다고 한다. 개발은 페어로 진행하는 것을 권장하는 방식이 인상적이었다..! 다음 글은 페어 프로그래밍에 대해서 읽어봐야겠다. 또한, 스터디를 자유롭게 제안하고 진행한다고 한다. 개발 테크 세미나를 열어서 진행한다는데 회사에 이러한 이벤트가 있다면 정말 많은 자극도 받고 함께 성장할 수 있겠다는 생각이 들었다.
    > - 혜택서비스팀
    > 시스템 기준으로 ‘쿠폰시스템’ 과 ‘혜택시스템’ 을 책임진다고 한다. 이렇게까지 읽다보니 팀내에서 기획자, 백엔드, 프론트엔드 개발자들이 함께하는 것을 알았다. 이후에 인터뷰를 찾아보니 우아한형제들 대부분의 개발 조직이 기획자와 개발자가 함께있는 목적조직으로 운영이 된다고 한다. 이 점이 내가 글로써 경험한 다른 기업과의 다른 점이기도 했다.(물론 자세히는 모르지만..) 1주 단위 스프린트를 운영하고있다고 하고, 다음 스프린트를 플래닝 할 때는 ‘스크럼 포커’ 라는 것을 사용한다고 한다. 찾아보니 일정을 세우기 위한 전략이라는데 입으로 숫자를 말하는 것이 아닌 포커처럼 숫자가 적힌 카드를 사용한다고 한다.. 이럼으로써 다른 사람들의 공수산정이 영향을 주는 것을 막는다고 한다. 오.. 굉장히 신기했다. 그리고 이 팀 역시 주기적으로 페어를 바꿔가며 페어 프로그래밍을 진행한다고 한다.
- [x] `5/30` [직업 만족도 상위 1% 의 비밀](https://story.baemin.com/2401/)
    > - _느낀점_ : 인터뷰를 통해서 우아한형제들이라는 회사의 이미지는 다음과 같았다. 스타트업과 큰회사의 장점이 결합된 환경이다. 하고 싶은 거가 있는데 큰 회사가 지원해주는 느낌이다. 이직해서 좋은 점은 직접 쓰는데 어렵지 않고 많은 사람들이 이용하는 도메인에서 일을 할 수 있다. 의견을 내기 자유롭고 잘 받아들여진다. 테스크 분배를 잘 해주셔서 일하기 좋다.
    > 
    > 그 중 스타트업과 큰 회사의 장점이라니… 안정적이지만 도전할 수 있는 환경이 얼마나 큰 시너지를 일으켰는지는 우아한형제들을 보면 알 수 있으리라 싶었다. 해당 글은 만화경이라는 팀의 인터뷰였다. 최근에는 만화경에서는 기존의 플랫폼에서는 볼 수없는 구름톡이라는 기능을 내놓았다고 한다. 구름톡이란 특정 장면에 대한 감상을 바로 입력할 수 있게 그리고 볼 수 있는 기능이다. 네이버 웹툰에 컷툰이 있는데 컷툰의 장점 중 하나는 컷마다 댓글을 달 수 있다는 점이 었다. 그런 점이 좀 더 자유롭게 반영이 되어서 작가와 독작 함께 웹툰을 만들어가는 것이지 않나 싶었다.
    > 
    > 개발적으로 웹툰이기 때문에 이미지에 대한 고민도 듣고 싶었는데 백엔드 개발자님이 나오셔서 이야기 해주셨다. 역시 더 적은 데이터를 써서 품질이 높은 이미지를 제공하는데 공을 많이 들인다고 한다. 최근에 iOS 개발잘 참여했던 프로젝트도 이미지의 다운로드하는 속도를 향상시키기 위해서 사용되는 목적에 따라서 리사이징하 이미지를 요청했던 것 같다. 이런 점들을 현업자분들은 어떻게 하시는지, 로직을 결정하는데 다가가는 과정은 어떠한지 더욱 궁금해졌다.
- [x] `5/31` [웹툰도 같이 봐요: 만화경 구름톡](https://techblog.woowahan.com/6803/)
    > - _느낀점_ : 작년 11월 만화경이라는 웹툰을 보는 앱에서 구름톡 신기능이 추가되었다. 기존 댓글이 에피소드 한 회차 전체에 대한 댓글이라고 한다면 구름톡은 에피소드 내의 특정 장면에 대해서 원고 바로 위에 남길 수 있는 댓글이다. 구현에 대한 이야기도 들어있었는데 너무 좋았다… 사용자가 원골르 스크롤함과 동시에 댓글을 보여주기 위해서 다음에 나타날 컷의 댓글을 미리 서버에서 호출한 뒤 원고가 화면에 보일 때 노출한다고 한다. 만들게 된 계기가 만화를 혼자 보는 것이 아니라 같이 보는 경험으로 만들어 보고 싶은 점이라고 한다. 예를 들어 스우파가 한창 유행할 때 유투버들은 라이브로 구독자와 방송을 같이 보거나 일반인들은 보는 장면을 실시간으로 SNS 에 공유했다. 이것이 방송을 보면서 느끼는 감정을 바로바로 사람들과 공유하고 공감하고 싶기 떄문이 아닐까 라는 글이었다. 구름톡은 웹툰이라는 컨텐츠를 재밌게 감상하는 또 하나의 방법을 제시했다고 생각한다. 
    > 
    > 구름톡의 시안은 다양하게 나왔다고 한다. 흘러가는 형식(현재 방식), 원하는 위치에 고정하는 형식, 라이브 채팅 형식 등등 그리고 사용성 테스트 후 현재 방식이 되었다고 한다. ‘사용자는 에피소드 장면 중에서도 자신이 원하는 위치에 댓글을 남길 수 있다.’ 라는 목표에 맞게 결정되었다고 한다, 실제 현업자분들의 시안이나 결정 과정을 보게 되니까 되게 두근댔다. 그리고 얼른 나도 의견을 내고 경험하고 공헌하고 싶었다.
    > 
    > 그리고 흘러가는 애니메이션이 있고, 어떤 타이밍에 어떻게 등장해야하는지가 있다보니까 잦은 베타 배포를 해야하는 점이 있었는데 베타에서 다양하게 세팅을 조절하면서 결정할 수 있도록 별도의 세팅 기능을 추가했고 이 점이 디테일을 결정하는데 큰 도움이 되었다고 한다. 정말 좋은 아이디어이고 나도 사용할 수도 있겠다고 생각했다! 
만화경 팀에 대한 가치간과 협업 과정 그리고 현업자분들의 아이디어를 엿볼 수 있었던 좋은 글이었다.
- [x] `6/4` [아무것도 준비하지 말고 그냥 오세요](https://story.baemin.com/3020/)
    > - _느낀점_ : 가장 궁금한 것 중에 하나이고, 가장 흥미로운 글 중 하나였다. 하하. 바로 웰컴 키트 소개다. 이전에 지마켓 글로벌의 웰컴 키트에 대한 글을 본적이 있었다. 그때 이후로 기업들의 웰켐 키트들에 대해 보는 것도 취업 자체에 대한 동기부여가 된다고 생각했다. 우아한형제들은 배달이라는 캐릭터와 민트라는 포인트 색이 떠오르는데 그대로 반영이 되었다. 민트색이 포인트로 있는 순백의 노트북 가방이라던지 텀블러가 있었다. 수저세트가 인상적이었고 ㅎㅎ 고체 치약과 칫솔 살균기도 주었다. 케이스에 이 "치약을 다 쓸때쯤이면 우리 팀원 이름은 다 외웠겠지?" 라는 멘트와 치약 30개가 있는데 요런 포인트가 취저였다. 위트라고 할까. 그리고 입사 기념 배달의민족 만원 쿠폰 30장..! 글에서 의도하신대로 키트에서 배민다움이 이라는 아이덴티티가 묻어나와서 신기했다.
- [x] `6/6` [2021 우아한형제들 경력 개발자 인터뷰 #1편](https://techblog.woowahan.com/2714/)
    > - _느낀점_ : 타 부서와의 협업은 어떻게 이루어지고 있을까에 대한 궁금증이 있었는데 읽을 수 있어서 좋았다. 배달의민족의 경우는 정기적으로 업데이트와 릴리즈를 하고 있고, 해당 업데이트 버번에 대한 회의를 위해서 안드, 서버, 기획, QA 개발자분들과 함께 논의한다고 한다. 슬랙을 사용해서 소통을 한다고 한다. 역시 회의든 일이든 커뮤니케이션이 중요하다고 한다. 또한, 다른 부서의 업무나 방식에 대한 이해의 노력도 필요하다고 한다. 나도 프로젝트를 하면서 나의 일만 내세우기보다는 상대방 파트의 일 방식이나 일정에 대해서 고려하기 위해 노력했던 기억이 있었다. 확실히 좋은 커뮤니케이션을 위해서는 그런 노력이 필요한 것 같다. 도한, 현업자들의 도전적인 과제에 대해서 귀하게도.. 들을 수 있었다. RIBs 라는 프레임워크를 도입이라고 했다. 팀원들이 많아지면서 통일된 관점과 방식으로 작업을 해야할 필요성을 느꼈고, RIBs 를 도입하면서 레거시 코드를 바꾸는 것이 힘든 부분이라고 했다. 또한 페어 프로그래밍으로 해결했다고 했다. 이정도면 좋은 방식이라는 것은 분명하다. 최근 RIBs 를 공부 중인데 비지니스 로직에 따라 아키텍처를 꾸릴 수 있는 점이 장점이라고 했고, 같은 종류의 파일은 공통적인 역할을 하다보니 분명 작업하는데 통일된 관점으로 수월하게 협업할 수 있겠다는 생각이 들었습니다.
- [x] `6/26` [iOS Networking and Testing](https://techblog.woowahan.com/2704/)
    > - _느낀점_ : URLSession 과 Alamofire, Moya 까지 만화경 iOS App 에서 어떻게 사용하고 있는지 알 수 있는 귀한 글이었다. 서버 통신 코드를 테스트할 때는 두 가지 방법이 있다. 첫 번재는 진짜로 네트워크 호출을 하는 것이다. 이 점은 느리고, 네트워크 상황에 따라서 결과가 달라질 수도 있다. 서버에서 코드를 잘 못 작성했거나 API 문서와는 다른 점이 있거나 등등 이런 경우에는 내 코드의 유효성과 관계없이 통신은 실패하고, 어디가 문제인지 처음부터 체크해야하는 리소스가 추가된다. 그렇기 때문에 테스트 코드를 작성하는 것은 중요하다고 한다. 실제로 현업의 테스트 방법에 대해서 읽을 수 있어서 좋았다. 참고해서 코드를 작성해 봐야겠다. 
- [x] `7/13` [[토크쇼] 프로덕트를 만드는 사람들-안 된다고 하지 말아요 개발자/디자이너/기획자 삼파전! : 6월 우아한테크세미나](https://www.youtube.com/watch?v=cdW77ljBggs&t=730s)
    > - _느낀점_ : 만화경팀의 안드로이드 개발자, 기획자, 디자이너분들이 나오셔서 만화경 팀 소개오 함께 협업과 여러가지 비하인드에 대해서 들을 수 있었다. 긴 시간의 세미나였지만 알차고 자세했던 만화경 팀의 구성과 출연자분들의 쉼 없는 입담 덕에 지루함없이 들을 수 있었다. ㅎㅎ 자기의 일을 자신있게 누군가에게 소개하고 알리는 행사 굉장히 멋있어 보였고 부러웠다. 부제가 "안된다고 하지 말아요." 였다. 부제를 보고 수락의 방식에는 다양한 것이 있듯이 거절의 방식도 다양하고 또 충분히 상대방은 존중받아야 한다고 생각했다. 그러면 어떻게 안된다고 말하지 않을까? 라고 궁금해하면서 들었던 것 같다. 내용 중에 스프린트 주기가 기획서가 나오고 디자인이 나오고 개발하고 QA 테스트를 거쳐서 회고를 하는 것이 큰 주기인데 그러면서 개발자분들이 해당 주기가 끝나고 다음 주기를 하기위해서 작업이 바로 들어가는데 이때 주기가 겹치게되는 것이 힘든 사항에 대해 언급해주셨다. 그런데 기획자분들과의 긴밀한 소통도 하고 스케줄을 잘 잡아주기 때문에 작업하는데 편했다고 한다. 정말 기획자 한명이 중요도를 많이 가져가는 것 같다고 생각했다. 여러가지 협업을 하다보니 나도 그렇지만 많은 파트의 리드분들도 서툴고 서로 맞춰나가는 점이 많았다. 이러한 과정을 통해서 만화경의 좋은 팀원들처럼 성장할 수 있다고 생각하기 때문에 겁먹지 말고 항상 배우는 자세로 도전하는 것도 중요하다고 생각이 들었다. 그리고 댓글창을 고도화했던 과정에 대해서도 소개해주셨다. 문제를 해결하는 방법을 도출하기 위한 과정과 문제라고 판단했던 이유 그리고 디자인과의 협업 그리고 개발자가 그 속에서 비슷한 기능에 대해서 통합하는 챌린지까지 그저 맡겨진 바를 수행하는데 그치는 것이 아니라 더 좋은 프러덕트와 코드를 위해서 개발자도 고민하는 과정도 보여주셨다. 그러면서 우아한 형제들에는 pit stop(피트 스탑)이라는 연례 행사가 있다고 한다. 바로 비즈니스 요구사항을 중단하고 급해서 미뤄놓았던 일들을 진행하거나 앞으로 일을 더 잘하기 위한 준비 기간이라고 한다. 개발자를 준비하는 내가 느끼기에 이 과정은 정말 필요하다고 느낀다. 최근에 읽은 클린코드책에서 이런 말이 있다. “기한을 맞추는 유일한 방법은, 그러니까 빨리 가는 유일한 방법은, 언제나 코드를 최대한 깨끗하게 유지하는 습관이다.”  내가 앞으로의 프로세스를 더 정확하고 빠르게 하기 위한 방법은 항상 내가 진행해온 프로세스에 대해서 돌아보고 정리해야한다고 생각한다. 그러면서 좋은 문화라고 느꼈다.

<div align=center>

## 파파고 iOS 개발자 Hong seongho[🔗](https://medium.com/@hongseongho)

</div>

- [x] `6/2` [2주간의 온라인 페어프로그래밍 회고](https://medium.com/@hongseongho/2주간의-온라인-페어프로그래밍-회고-c5796bfa77c1)
    > - _느낀점_ : 페어프로그래밍에 대한 글을 찾다가 파파고 iOS 개발자분의 글을 봤다. 온라인으로 페어프로그래밍을 진행하셨고,30분+10분 의 조합으로 하셨다 한다. 나는 둘이서 이야기를 하면서 진행할테니까 생각보다 시간이 되게 빠르게 갈 것 같은데? 라고 생각했다. 처음에 이분들도 50분+10분 으로 했었는데 페어프로그래밍을 경험한 최대의 단점인 체력이 빨리 떨여진다는 이유로 줄이셨다. 심지어 온라인으로 진행하다 보니 줌을 통해 상대방의 말을 듣고 이야기를 전달하는 것이 에너지 소모가 많다고 했다. 또한, 오프라인에서는 키보드만 넘겨받으면 그만이지만 온라인은 커밋을 하거나 클린빌드를 해야할 때가 있어서 좀 더 부수적인 시간이 때문에 온라인과 오프라인 시간은 다르게 조율하는 것이 좋다고 한다. 뚜렷한 장점에 대해서는 개인이 PR 을 올릴 때는 코드를 완전히 갈아엎는 작업에 대해서 거부감이 생기기 마련인데 페어 프로그래밍을 진행하면서 코드의 오너쉽이 팀에 있다는 것을 은연 중에 알게된다고 했다. 적재적소에 사용하고, 규칙도 열심히 만든다면 오프라인이든 온라인이든 효과적인 방법이라는 생각이 들었다.

<div align=center>
 
## 토스 youtube[🔗](https://www.youtube.com/user/TOSSservice)

</div>

- [x] `8/12`[토스ㅣSLASH 22 - 미친 생산성을 위한 React Native](https://www.youtube.com/watch?v=b_6CjuvVg8o)
    > - _느낀점_ : React Native 를 실제로 토스 글로벌 앱에 도입하여 네이티브의 단점과 당시의 토스 글로벌 팀의 상황에 따라서 React Native 의 장점을 Flutter 와 비교하며 감수할 부분은 감수하며 진행하게된 과정과 이유, 프로세스에 대해서 자세히 설명해주어 쉽게 납득할 수 있었다. 사용자 대부분의 스마트폰 기종과 기능에 따라서, 업데이트 빈도에 따라서 언어를 선택하는 과정을 보여주었다. 매우 자세하고 논리적이어서 같이 고민하는 듯한 느낌도 들었다. 또한, 스위프트 개발자님의 고민인 스위프트 경력이 단절되거나 리액트 네이티브의 앞으로에 대한 걱정 등 팀이 아닌 개인에 대한 고민했던 점도 얘기해주셔서 더 다가왔던 것 같다. 토스 slash 22 시리즈를 쭉 보면서 토스가 좀 더 어떤 기업인지 알 수 있겠다고 느꼈다.
- [ ] [토스ㅣSLASH 22 - UIKit으로 만들어진 토스 디자인 시스템, SwiftUI에서 쓸 수 있을까?](https://www.youtube.com/watch?v=q0CX-0k2l0g&list=PL1DJtS1Hv1PiGXmgruP1_gM2TSvQiOsFL&index=22)
- [ ] [토스ㅣSLASH 22 - iOS앱을 매주 배포 한다고?](https://www.youtube.com/watch?v=GhcJ-KDFLrU&list=PL1DJtS1Hv1PiGXmgruP1_gM2TSvQiOsFL&index=5)

## NAVER WEBTOON[🔗](https://recruit.webtoonscorp.com/main.do)
- [x] `9/20` [네이버웹툰 신입 개발자의 성장 일기](https://recruit.webtoonscorp.com/cnts/story_detail?id=11&utm_source=%08insidepost&utm_medium=%08insidepost_page&utm_campaign=basic)
    > - _느낀점_ : 2021 네이버웹툰 신입 개발자분들의 인터뷰를 읽게되었다. 어떻게 커리어를 시작해서 나아가시는지 궁금했다. 대부분의 분들이 네이버에서 진행하는 다양한 행사에 참여하면서 네이버웹툰의 개발 문화를 통해서 선택하셨다고 하셨다. 가까운 곳에서 네이버웹툰의 개발 문화를 경험해 볼 수 있는 경험이 부러웠다. 면접문화가 다른 기업에 비해서 조금 달랐다. 이때는 손 코딩도했다는데 최근 공고에서는 라이브 코딩을 할 예정이다. 사내 컨퍼런스와 스터디제도가 있다고 했다. 이런 경험을 나도 꼭 하고 싶다고 생각했다. 합격자분들의 어려웠던 점은 프로젝트의 히스토리를 이해하는데 많은 리소스가 든다고 하셨다. 레거시코드도 그렇고 아키텍처에 대해서 이해하기 위해서는 사내 위키 등 많은 노력이 필요하겠다고 생각했다. 예비 취준생들한테 하는 말씀이 가장 와닿았다. 준비하는 과정에서만 배울 수 있는 것이 있고, 많다라는 것에 동의한다. 또한, 네이버웹툰은 웹툰, 웹소설과 영상까지 다양한 개발을 경험해볼 수 있는 것이 장점이라고 하셨다.
- [x] `9/21` [개발자의 커리어로 네이버웹툰을 선택한 이유](https://recruit.webtoonscorp.com/cnts/story_detail?id=17&utm_source=%08insidepost&utm_medium=%08insidepost_page&utm_campaign=basic)
    > - _느낀점_ : 이번에는 2022 네이버웹툰 경력 개발자 공고를 앞두고 새롭게 합류한분들의 이야기를 들어볼 수 있었다. 한국에 있는 글로벌 서비스를 운영하는 기업이라는 점을 고려하신분도 계셨고, 자신의 핸드폰에 설치된 앱들 중 사용횟수를 통해 리스트업하고 지원하게된 분도 계셨다. 기술과 콘텐츠를 접목시킬 수 있다는 부분에서 지원한 분도 계셨다. 모두 네이버웹툰의 강점이라고 생각이 들었다. 업무를 진행하면서 어려웠던 점도 들을 수 있었다. 최근 바람이 많이 불고 있는 비대면 회의에 대한 부분도 읽을 수 있었다. 팀끼리 얼굴을 보지 못하거나 제스처와 같은 비언어적인 메시지 전달에 어려움을 느끼셨다고 했다. iOS 개발자가 유독 많다고 하셨다. 이때 팀의 룰을 정하고 지키는 것도 어려움이라고 하셨다. 컨밴션에 대한 중요성을 다시금 느꼈다. 그만큼 많은 개발자들과 함께 코드를 리뷰하고 이야기해볼 수 있는 기회가 생기셨다고 하셨다. 이 과정에서 넓은 시야와 바라보는 리스크의 수준도 배울 수 있으셨다고 하셨다. 현재 웹툰을 기반으로한 사업들이 성장하고 있다. 그래서 콘텐츠 산업에 많은 관심이 향하고 있는데 이러한 카테고리를 가진 개발을 하는 것은 소중한 경험이 쌓일 것 같다. 경력 개발자분들이 느끼시기도 유저 수가 많은 것이 많은 트래픽 처리로 이어지고 또한, 글로벌한 문화를 경험하는 것도 이점이라고 하셨다. 또한, 사내 스터디 문화가 굉장히 활발해 보였다. 이러한 사내 문화를 희망하기때문에 네이버웹툰도 좋은 회사라고 느꼈다. 종합적으로 콘텐츠를 양방향으로 다루는 앱인 네이버웹툰에 대한 강점을 많이 읽을 수 있었고, 개발자에 대한 관심, 지원 그리고 사내 컨퍼런스, 스터디 등이 매우 활발해 보였다. 기술적인 다양함과 깊이로 콘텐츠를 얼마나 잘 노출시킬 수 있느냐를 항상 고민할 수 있는 곳인 것 같다. 그러다 보니 자연스레 기술적인 성장에 대해서 목마름이 있는 것 같다.
