# Git and GitHub 용어



#### commit

------

하나 또는 다수의 파일에 변경 내용을 저장할 때마다 새로운 commit을 생성한다.

예: "이 변경 내용을 commit하고 이를 GitHub에 push합시다."



#### commit message

------

commit을 생성할 때마다 왜 변경을 하였는지에 대한 이유를 설명하는 메시지를 제공해야 한다. 이 commit message는 변경을 한 이유를 나중에 이해하기 위해 매우 유용하다.

예: "새로운 SEC 가이드라인에 대한 Alice의 의견을 commit message에 꼭 넣어주세요."



#### branch

------

테스트를 해보거나 새로운 기능을 개발하기 위해 사용할 수 있는  따로 떨어진 독립된 commit을 말한다.

예: "새로운 검색 기능을 구현하기 위해 branch를 만듭시다."



#### master branch

------

새로운 git 프로젝트를 만들 때마다 master라고 하는 기본 branch가 만들어진다. 배포할 준비가 되면 작업이 최종적으로 마무리되는 branch이다.

예: "master로 바로 commit하면 안된다는 것을 기억하십시오."



#### feature / topic branch

------

새로운 기능을 개발할 때마다 작업할 branch를 만드는데 이를 feature branch라고 한다.

예: "feature branch가 너무 많습니다. 이들 중 하나나 두 개를 완료해서 출시하는데 주력합시다."



#### release branch

------

직접 QA(Qualtity Assurance; 품질 보증) 작업을 하거나 고객의 요구로 구 버전의 소프트웨어를 지원해야 한다면 모든 수정이나 업데이트를 위한 장소로 release branch가 필요하다. feature branch와 release branch는 기술적인 차이는 없지만, 팀원들과 프로젝트에 대해 얘기할 때 확연히 구별할 수 있어 유용하다. 

예: "release branch 전체에 대한 보안 버그를 수정해야 합니다."



#### merge

------

merge는 한 branch에서 완성된 작업을 가져와 다른 branch에 포함시키는 방법이다. 흔히 feature branch를 master branch로 병합(merge)한다.

예: "A 기능이 훌륭합니다. 배포할 수 있도록 master로 merge해 줄 수 있겠습니까?"



#### tag

------

특정 이력이 있는 commit에 대한 참조이다. 어떤 버전의 code가 언제 release되었는지 정확히 알 수 있도록 제품 배포 기록에 가장 자주 사용한다.

예: "이번 배포판에 tag를 달아 출시합시다."



#### check out

------

프로젝트 history의 다른 버전으로 이동해 해당 시점의 파일을 보기위해  check out한다. 가장 일반적으로 branch에서 완료된 작업을 모두 보기 위해 branch를 check out하지만 commit도 check out할 수 있다.

예: "최종 release tag를 check out해주시겠어요? 제품에  버그가 있어서 검증하고 수정해야 합니다."



#### Pull request

------

원래 pull request는 branch에서 완료된 작업을 다른 사람이 review하고 master로 병합하도록 요청하기 위해 사용한다. 요즘은 개발 가능한 가능에 대한 논의를 시작하는 초기 작업 단게에서 자주 사용한다.

예: "다른 팀원들이 어떻게 생각하는지 알 수 있게 새로운 투표 기능에 대한 pull request를 만들어주세요."



#### Issue

------

GitHub는 기능에 대해 논의하거나 버그를 추적하거나 또는 두 가지 경우 모두에 사용할 수 있는 issue라는 기능을 갖고 있다.

예: "당신이 옳습니다. 아이폰에서는 로그인이 되지 않습니다. 버그를 검증하기 위한 단계를 기록하면서 GitHub에 issue를 만들어 주세요."



#### clone

------

종종 local로 작업하기 위하여 프로젝트 복사본을 GitHub에서 다운로드한다. repository를 사용자의 컴퓨터로 복사하는 과정을 cloning이라고 한다.

예: "repository를 clone하고 버그를 수정한 다음 오늘 밤 수정본을 다시 GitHub로 push해주시겠습니까?"



#### Fork

------

때로는 프로젝트를 직접 변경하는데 필요한 권한을 보유하지 못할 때가 있다. 잘 알지 못하는 사람이 작성한 오픈 소스 프로젝트이거나 회사에서 작업을 같이 많이 하지 않은 다른 그룹이 작성한 프로젝트일 수도 있다. 그러한 프로젝트를 변경하고 싶다면 먼저 GitHub의 사용자 계정에 프로젝트 복사본을 만들어야 한다. 이 과정을 'repository를 fork한다'고 한다. 그런 다음 clone하고, 변경하며 pull request를 이용해 원본 프로젝트에 변경 내용을 반영할 수 있다. 

예: "홈페이지 마케팅 원고를 당신이 어떻게 재작성했는지 보고 싶습니다. repository를 fork해서 수정안과 함께 pull request를 해주세요."
