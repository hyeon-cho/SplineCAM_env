## SplineCAM 환경 설정 

1. `conda create -n gt-torch -c conda-forge --override-channels python=3.8 pytorch pytorch_geometric torch-scatter graph-tool==2.45` 로 일단 설치 
2. 이후pytorch 1.12.1 버전을 다음과 같이 재설치 [link](https://github.com/hpcaitech/ColossalAI/issues/2901#issuecomment-1445668699 )

torchvision warning 이 뜨긴하지만 일단 돌아감
