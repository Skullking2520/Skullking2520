# 현준수 담당 범위 · 뭉치 AI

[프로필로 돌아가기](../README.md) · [원본 팀 저장소](https://github.com/V-MoongCheap/MoongCheap-AI/tree/develop)

## 수행 배경과 역할

kt cloud TECH UP 통합 팀 프로젝트의 AI 파트입니다. 현준수는 **AI 파트장**으로 일정과 협업 소통을 맡고, 기술적으로 데이터 기반 구성·Facet·자연어 수요 라벨링(A파트)을 담당했습니다.

| 구분 | 담당 내용 |
| --- | --- |
| 파트 운영 | 전체 일정 조율, 타 파트와 협업 관리, 프로젝트 진행상황 소통 |
| 데이터 기반 | 상품·소비자 표현 등 자료 수집·전처리와 사용 범위 정리 |
| Facet·분류체계 | 속성·값·별칭 후보, 근거 검증과 사람 검토를 통한 기준 정리 |
| 수요 라벨링 | 자연어 요구를 분류체계에 연결하는 Rule-first Hybrid와 검증 처리 |
| 연계·실행 | A파트 결과를 후속 처리와 연결하고 배치·DB 저장 경로를 보완 |

수요 클러스터링, 판매자 매칭과 판매자 분석은 다른 AI 팀원의 주요 담당 영역입니다. 파트장으로 조율한 범위와 직접 담당한 A파트의 기술 작업을 구분합니다.

## 기술 작업을 보는 순서

1. [문서 상태와 현재 기준](https://github.com/V-MoongCheap/MoongCheap-AI/blob/develop/docs/DOCUMENT_STATUS.md)
2. [데이터 계보](https://github.com/V-MoongCheap/MoongCheap-AI/blob/develop/docs/DATA_LINEAGE.md)
3. [모델·방식 선택 근거](https://github.com/V-MoongCheap/MoongCheap-AI/blob/develop/docs/MODEL_SELECTION_FINAL_V1.md)
4. [A파트 검증 정책](https://github.com/V-MoongCheap/MoongCheap-AI/blob/develop/docs/A_RUNTIME_VALIDATION_POLICY.md)
5. [A파트 실행·배포 확인 기록](https://github.com/V-MoongCheap/MoongCheap-AI/blob/develop/docs/A_LABELING_SMOKE_TEST.md)
6. [A–B 연계 계약](https://github.com/V-MoongCheap/MoongCheap-AI/blob/develop/docs/PART_B_V22_INTEGRATION.md)

## 설계와 결과의 범위

모델이 만든 후보를 그대로 확정하지 않고, 분류체계와 원문 근거 검증 및 사람 검토를 구분했습니다. 라벨링은 명확한 규칙을 우선 적용하고, 미해결 요구에 제한적으로 모델을 사용하도록 구성했습니다.

과거 비교 실험, 현재 저장 정책, 배포 확인은 서로 다른 기록입니다. 문서에 남은 이전 실험 점수를 이후 수정된 코드의 정확도로 제시하지 않습니다. 완료된 제출 산출물의 범위와 후속 개선 과제는 [현재 기준 문서](https://github.com/V-MoongCheap/MoongCheap-AI/blob/develop/docs/DOCUMENT_STATUS.md)를 따릅니다.
