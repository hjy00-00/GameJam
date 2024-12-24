## GameJam

# WebGL 빌드 파일 다운로드 및 사용 방법

# 1. 분할된 압축 파일 다운로드:
#   저장소에서 `output.zip`, `output.z01`, `output.z02` 등의 파일을 다운로드합니다.

# 2. 분할 압축 파일 병합 및 해제:
#   다운로드한 파일을 같은 폴더에 저장한 후, 아래 명령어를 실행합니다:

   zip -s 0 output.zip --out merged.zip
   unzip merged.zip
