# CUDA setting

## STEP 1 

> ### NVIDIA driver 
> [사이트 링크](https://www.nvidia.co.kr/Download/index.aspx?lang=kr)
> 한글이니 들어가서 보고 세팅해서 다운하자 ( 내 그래픽카드를 모른다면 장치관리자->디스플레이 어댑터)
> #### 성공했다면 당신의 컴퓨터에는 NVIDIA 제어판이 있을것이다.... 없다면 유감...

## STEP 2

> ### GPU Compute Capability 확인하기!
> 
>[사이트 링크](https://developer.nvidia.com/cuda-gpus)
>
>![제목 없음](https://user-images.githubusercontent.com/65435447/163527415-e78e546d-82be-474f-9fea-225a8c826ac7.png)
>
> 그렇다... 난 RTX3090이다...

## STEP 3

> ### Pytorch
> 그렇다 난 torch를 사용할것이다... 만약 다른걸 쓸려면 그곳 사이트에서 호완성을 확인하자...
> 
> [사이트 링크](https://pytorch.org/get-started/locally/)
> 
> 다운로드할 CUDA 버전을 확인하고 CUDA를 다운하자...

## STEP 4

> ### CUDA 설치
> [사이트 링크](https://developer.nvidia.com/cuda-toolkit-archive) 
> 
> 앞에서 확인한 CUDA 버전 다운
> 
> * 주의 * STEP 2에서 확인한 Capability를 [링크](https://en.wikipedia.org/wiki/CUDA)에서 GPUs supported항목에서 확인한다.
> 
> ![image](https://user-images.githubusercontent.com/65435447/163528797-cd883ee0-c504-463a-bf96-9da58f194b97.png)
> 
> 그렇다.. RTX 3090은 CUDA 11.3을 지원한다... 고사양 쵝오

## STEP 5

> ### cuDNN 설치
> 
>[사이트 링크](https://developer.nvidia.com/cuda-toolkit-archive)
>
>그렇다... 아이디를 만들어야한다... 공인인증서가 아니라 다행이다
>
>STEP 4에서 설치한 CUDA 버전에 마추어 설치하자 
>
> 난 CUDA 11.3이였기에 cuDNN v8.2.1 (June 7th, 2021), for CUDA 11.x을 설치하였다. 그리고 난 윈도우기에 cuDNN Library for Windows (x86)을 설치하였다.

## STEP 6

> ### 다운로드한 CUDA 파일 실행, 설치
> 
> ### 다운로드한 cuDNN 파일 압축 풀기
> CUDA 설치 폴더에 가서 cuDNN안에 있는 파일들을 옮겨준다.
> 옮긴 파일 위치를 환경 변수 설정에서 path에 추가한다.

# 끝!






