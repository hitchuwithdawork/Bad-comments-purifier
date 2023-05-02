# 악성 댓글 순화 프로젝트

### 프로젝트 소개

- 사용자가 입력한 댓글에 대하여 비윤리적 표현이 발견될 경우 해당 표현을 윤리적으로 순화하는 프로젝트.
---
### 사용 데이터

- [AI hub 텍스트 윤리 검증 data set](https://aihub.or.kr/aihubdata/data/view.docurrMenu=115&topMenu=100&aihubDataSe=realm&dataSetSn=558)
- [Korean HateSpeech Dataset](https://github.com/kocohub/korean-hate-speech)
---
### 사용 기술
- 딥러닝 모델 : pretrained된 KcELECTRA, kogpt2

- 사용 라이브러리 : Huggingface, Pytorch, streamlit , wandb

---
### 프로젝트 정리
- [프로젝트 ppt 링크](https://github.com/hitchuwithdawork/Bad-comments-purifier/blob/master/Bad%20comment%20purifier.pdf)
---
### 참고 논문
*  Delete, Retrieve, Generate: a Simple Approach to Sentiment and Style Transfer (Li et al., NAACL 2018)
*  Unpaired Korean Text Style Transfer with Masked Language Model (배장성, et al. 2021)
*  Stable Style Transformer: Delete and Generate Approach with Encoder-Decoder for Text Style Transfer (Joosung Lee, 2020)

---
### 참고 github
* https://github.com/rungjoo/Stable-Style-Transformer
* https://github.com/agaralabs/transformer-drg-style-transfer
* https://github.com/Beomi/KcELECTRA
* https://github.com/SKT-AI/KoGPT2
