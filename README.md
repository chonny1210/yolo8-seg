# yolo8-seg

# 포트폴리오 프로젝트 모음

이 저장소에는 YOLO8 seg 모델을 활용하여 내시경(위/대장) 파일럿 프로젝트가 포함되어 있습니다. 


---

## 프로젝트 목록

### 1. 유동인구 카운트 YOLO 영상 파일럿 프로젝트
- **프로젝트 설명**: YOLO 모델을 사용하여 영상 속 유동인구를 실시간으로 감지하고, 입장 및 퇴장 수를 카운트하는 시스템.
- **주요 기능**: 사람 객체 탐지, 입장 및 퇴장 카운팅, 누적 인원 계산.
- **관련 링크**:
  - [YOLO 모델 다운로드](https://github.com/ultralytics/yolov5)
  - [OpenCV 공식 문서](https://docs.opencv.org/)
- **시연 영상**:  
[![유동인구 카운트 영상](https://github.com/oracleyu01/pilot/blob/main/sjk.jpg)](https://github.com/oracleyu01/pilot/blob/main/sjk_with_counts_vrew_exported.mp4)



## 설치 및 실행 방법

1. 필요한 라이브러리 설치:
   ```bash
   pip install opencv-python-headless ultralytics numpy​
