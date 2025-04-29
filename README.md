# [10가지 프로젝트로 끝내는 트랜스포머 활용 가이드 with 파이토치] book6 번역본 코드 관련 정보
# 원제: Building Transformer Models with PyTorch 2.0 

# 지은이 프렘 팀시나, 옮긴이 임선집, 감수 채호창
# 2025년 02월 07일 발행, 루피페이퍼 

# 발행인 한창훈, 편집 김은숙

### 책 출간 후 코드 수정 사항
독자 여러분의 피드백으로 다음과 같이 깃허브의 책 코드 중 관련 부분을 수정해 업로드했습니다. 
피드백을 보내주신 독자 여러분께 감사드립니다.
기존 코드: from transformers import AdamW
변경 코드: from torch.optim import AdamW
변경 사유: transformers에서 더 이상 AdamW를 제공하지 않아서 이를 반영하였습니다.

다음의 링크를 통해 책에서 활용된 예제 소스를 내려받을 수 있습니다.
■ 한글 번역본 예제 소스 _ https://github.com/jasonyim2/book6

원서에서는 터미널 및 아나콘다 환경을 사용하지만, 번역본에서는 해당 예제 소스를 구글 코랩에서 실행되도록 조
치해두었습니다. 따라서 입문 독자라면 가급적 한글 번역본 예제 소스를 사용하기 바랍니다.
원서에서 제공하는 원본 코드를 직접 다운로드하려면 다음의 링크를 참고하기 바랍니다.

■ 영어 원서 코드 및 컬러 이미지 _ https://rebrand.ly/hydtz8g
■ 영어 원서 코드(GitHub) _ https://github.com/bpbpublications/Building-Transformer-Modelswith-PyTorch-2.0

이 책을 읽다가 궁금한 점이 생기거나, 오류를 발견한다면 다음의 메일로 제보해주세요.

# ■ 한글 번역본에 대한 질의(역자) _ jasonyim@naver.com
# ■ 영어 원서에 대한 질의(저자) _ errata@bpbonline.com

