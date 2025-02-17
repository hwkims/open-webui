# Open WebUI 👋

![GitHub stars](https://img.shields.io/github/stars/open-webui/open-webui?style=social)
![GitHub forks](https://img.shields.io/github/forks/open-webui/open-webui?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/open-webui/open-webui?style=social)
![GitHub repo size](https://img.shields.io/github/repo-size/open-webui/open-webui)
![GitHub language count](https://img.shields.io/github/languages/count/open-webui/open-webui)
![GitHub top language](https://img.shields.io/github/languages/top/open-webui/open-webui)
![GitHub last commit](https://img.shields.io/github/last-commit/open-webui/open-webui?color=red)
![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Follama-webui%2Follama-wbui&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)
[![Discord](https://img.shields.io/badge/Discord-Open_WebUI-blue?logo=discord&logoColor=white)](https://discord.gg/5rJgQTnV4s)
[![](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86)](https://github.com/sponsors/tjbck)

**Open WebUI는 완전한 오프라인 작동을 위해 설계된 확장 가능하고 기능이 풍부하며 사용자 친화적인 자체 호스팅 AI 플랫폼입니다.** Ollama 및 OpenAI 호환 API와 같은 다양한 LLM 러너를 지원하며, RAG를 위한 **내장 추론 엔진**을 갖추고 있어 **강력한 AI 배포 솔루션**입니다.

자세한 내용은 [Open WebUI Documentation](https://docs.openwebui.com/)을 확인하십시오.

![Open WebUI Demo](./demo.gif)

## Open WebUI의 주요 기능 ⭐

- 🚀 **간편한 설정**: Docker 또는 Kubernetes (kubectl, kustomize 또는 helm)를 사용하여 `:ollama` 및 `:cuda` 태그 이미지를 모두 지원하는 번거로움 없는 설치를 경험하세요.

- 🤝 **Ollama/OpenAI API 통합**: Ollama 모델과 함께 OpenAI 호환 API를 쉽게 통합하여 다양한 대화를 지원합니다. OpenAI API URL을 사용자 정의하여 **LMStudio, GroqCloud, Mistral, OpenRouter 등**과 연결할 수 있습니다.

- 🛡️ **세분화된 권한 및 사용자 그룹**: 관리자가 자세한 사용자 역할 및 권한을 생성할 수 있도록 하여 안전한 사용자 환경을 보장합니다. 이러한 세분성은 보안을 강화할 뿐만 아니라 사용자 정의된 사용자 경험을 가능하게 하여 사용자 간의 책임감과 소유 의식을 조성합니다.

- 📱 **반응형 디자인**: 데스크톱 PC, 노트북 및 모바일 장치에서 원활한 환경을 즐기세요.

- 📱 **모바일용 프로그레시브 웹 앱 (PWA)**: PWA를 통해 모바일 장치에서 네이티브 앱과 같은 환경을 즐기세요. localhost에서 오프라인 액세스와 원활한 사용자 인터페이스를 제공합니다.

- ✒️🔢 **완전한 Markdown 및 LaTeX 지원**: 풍부한 상호 작용을 위해 포괄적인 Markdown 및 LaTeX 기능으로 LLM 경험을 향상시키세요.

- 🎤📹 **핸즈프리 음성/영상 통화**: 통합된 핸즈프리 음성 및 영상 통화 기능으로 원활한 커뮤니케이션을 경험하여 더욱 역동적이고 상호 작용적인 채팅 환경을 제공합니다.

- 🛠️ **모델 빌더**: 웹 UI를 통해 Ollama 모델을 쉽게 생성하세요. 사용자 정의 캐릭터/에이전트를 생성 및 추가하고, 채팅 요소를 사용자 정의하고, [Open WebUI Community](https://openwebui.com/) 통합을 통해 쉽게 모델을 가져올 수 있습니다.

- 🐍 **네이티브 Python 함수 호출 도구**: 도구 작업 공간에서 내장된 코드 편집기 지원으로 LLM을 향상시키세요. 순수 Python 함수를 추가하여 BYOF(Bring Your Own Function)를 구현하고 LLM과 원활하게 통합할 수 있습니다.

- 📚 **로컬 RAG 통합**: 획기적인 RAG(Retrieval Augmented Generation) 지원으로 채팅 상호 작용의 미래를 경험하세요. 이 기능은 문서 상호 작용을 채팅 경험에 원활하게 통합합니다. 문서를 채팅에 직접 로드하거나 문서 라이브러리에 파일을 추가하고 쿼리 전에 `#` 명령을 사용하여 쉽게 액세스할 수 있습니다.

- 🔍 **RAG를 위한 웹 검색**: `SearXNG`, `Google PSE`, `Brave Search`, `serpstack`, `serper`, `Serply`, `DuckDuckGo`, `TavilySearch`, `SearchApi` 및 `Bing`과 같은 공급자를 사용하여 웹 검색을 수행하고 결과를 채팅 경험에 직접 삽입합니다.

- 🌐 **웹 브라우징 기능**: `#` 명령과 URL을 사용하여 웹 사이트를 채팅 경험에 원활하게 통합합니다. 이 기능을 사용하면 웹 콘텐츠를 대화에 직접 통합하여 상호 작용의 풍부함과 깊이를 향상시킬 수 있습니다.

- 🎨 **이미지 생성 통합**: AUTOMATIC1111 API 또는 ComfyUI (로컬) 및 OpenAI의 DALL-E (외부)와 같은 옵션을 사용하여 이미지 생성 기능을 원활하게 통합하여 동적 시각적 콘텐츠로 채팅 경험을 풍부하게 합니다.

- ⚙️ **다중 모델 대화**: 여러 모델과 동시에 쉽게 상호 작용하여 최적의 응답을 위해 고유한 강점을 활용합니다. 다양한 모델을 병렬로 활용하여 경험을 향상시키세요.

- 🔐 **역할 기반 액세스 제어 (RBAC)**: 제한된 권한으로 안전한 액세스를 보장합니다. 권한이 있는 개인만 Ollama에 액세스할 수 있으며, 관리자에게만 모델 생성/가져오기 권한이 부여됩니다.

- 🌐🌍 **다국어 지원**: 국제화 (i18n) 지원을 통해 원하는 언어로 Open WebUI를 경험하세요. 지원되는 언어를 확장하는 데 함께 해주세요! 적극적으로 기여자를 찾고 있습니다!

- 🧩 **파이프라인, Open WebUI 플러그인 지원**: [Pipelines Plugin Framework](https://github.com/open-webui/pipelines)를 사용하여 사용자 정의 로직 및 Python 라이브러리를 Open WebUI에 원활하게 통합합니다. Pipelines 인스턴스를 시작하고, OpenAI URL을 Pipelines URL로 설정하고, 무한한 가능성을 탐색하세요. [예시](https://github.com/open-webui/pipelines/tree/main/examples)에는 **함수 호출**, 액세스 제어를 위한 사용자 **속도 제한**, Langfuse와 같은 도구를 사용한 **사용량 모니터링**, 다국어 지원을 위한 **LibreTranslate를 사용한 실시간 번역**, **유해 메시지 필터링** 등이 포함됩니다.

- 🌟 **지속적인 업데이트**: 정기적인 업데이트, 수정 및 새로운 기능을 통해 Open WebUI를 개선하기 위해 최선을 다하고 있습니다.

Open WebUI의 기능에 대해 더 자세히 알고 싶으신가요? 포괄적인 개요는 [Open WebUI documentation](https://docs.openwebui.com/features)을 확인하세요!

## 🔗 Open WebUI Community도 확인하세요!

자매 프로젝트인 [Open WebUI Community](https://openwebui.com/)를 둘러보는 것을 잊지 마세요. 이곳에서 사용자 정의된 Modelfile을 발견하고, 다운로드하고, 탐색할 수 있습니다. Open WebUI Community는 Open WebUI와의 채팅 상호 작용을 향상시키기 위한 다양하고 흥미로운 가능성을 제공합니다! 🚀

## 설치 방법 🚀

### Python pip를 통한 설치 🐍

Open WebUI는 Python 패키지 설치 프로그램인 pip를 사용하여 설치할 수 있습니다. 진행하기 전에 호환성 문제를 피하기 위해 **Python 3.11**을 사용하고 있는지 확인하세요.

1. **Open WebUI 설치**:
   터미널을 열고 다음 명령을 실행하여 Open WebUI를 설치합니다.

   ```bash
   pip install open-webui
   ```

2. **Open WebUI 실행**:
   설치 후 다음을 실행하여 Open WebUI를 시작할 수 있습니다.

   ```bash
   open-webui serve
   ```

그러면 Open WebUI 서버가 시작되며 [http://localhost:8080](http://localhost:8080)에서 액세스할 수 있습니다.

### Docker를 사용한 빠른 시작 🐳

> [!NOTE]  
> 특정 Docker 환경에서는 추가 구성이 필요할 수 있습니다. 연결 문제가 발생하면 [Open WebUI Documentation](https://docs.openwebui.com/)의 자세한 가이드가 도움을 드릴 것입니다.

> [!WARNING]
> Docker를 사용하여 Open WebUI를 설치할 때 Docker 명령에 `-v open-webui:/app/backend/data`를 포함해야 합니다. 이 단계는 데이터베이스가 올바르게 마운트되고 데이터 손실을 방지하는 데 중요합니다.

> [!TIP]  
> Ollama가 포함된 Open WebUI 또는 CUDA 가속을 사용하려면 `:cuda` 또는 `:ollama`로 태그가 지정된 공식 이미지를 사용하는 것이 좋습니다. CUDA를 활성화하려면 Linux/WSL 시스템에 [Nvidia CUDA 컨테이너 툴킷](https://docs.nvidia.com/dgx/nvidia-container-runtime-upgrade/)을 설치해야 합니다.

### 기본 구성을 사용한 설치

- **Ollama가 컴퓨터에 있는 경우** 다음 명령을 사용합니다.

  ```bash
  docker run -d -p 3000:8080 --add-host=host.docker.internal:host-gateway -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:main
  ```

- **Ollama가 다른 서버에 있는 경우** 다음 명령을 사용합니다.

  다른 서버의 Ollama에 연결하려면 `OLLAMA_BASE_URL`을 서버의 URL로 변경합니다.

  ```bash
  docker run -d -p 3000:8080 -e OLLAMA_BASE_URL=https://example.com -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:main
  ```

- **Nvidia GPU 지원으로 Open WebUI를 실행하려면** 다음 명령을 사용합니다.

  ```bash
  docker run -d -p 3000:8080 --gpus all --add-host=host.docker.internal:host-gateway -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:cuda
  ```

### OpenAI API 전용 설치

- **OpenAI API만 사용하는 경우** 다음 명령을 사용합니다.

  ```bash
  docker run -d -p 3000:8080 -e OPENAI_API_KEY=your_secret_key -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:main
  ```

### 번들 Ollama 지원과 함께 Open WebUI 설치

이 설치 방법은 Open WebUI와 Ollama를 번들로 제공하는 단일 컨테이너 이미지를 사용하여 단일 명령으로 간소화된 설치를 가능하게 합니다. 하드웨어 설정에 따라 적절한 명령을 선택하십시오.

- **GPU 지원 포함**:
  다음 명령을 실행하여 GPU 리소스를 활용합니다.

  ```bash
  docker run -d -p 3000:8080 --gpus=all -v ollama:/root/.ollama -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:ollama
  ```

- **CPU 전용**:
  GPU를 사용하지 않는 경우 이 명령을 대신 사용하십시오.

  ```bash
  docker run -d -p 3000:8080 -v ollama:/root/.ollama -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:ollama
  ```

두 명령 모두 Open WebUI와 Ollama를 번거로움 없이 설치할 수 있도록 지원하여 모든 것을 신속하게 시작하고 실행할 수 있도록 합니다.

설치 후 [http://localhost:3000](http://localhost:3000)에서 Open WebUI에 액세스할 수 있습니다. 즐기세요! 😄

### 기타 설치 방법

Docker Compose, Kustomize, Helm과 같은 Docker 외 기본 설치 방법을 포함한 다양한 설치 대안을 제공합니다. 자세한 내용은 [Open WebUI Documentation](https://docs.openwebui.com/getting-started/)을 방문하거나 [Discord community](https://discord.gg/5rJgQTnV4s)에 참여하세요.

### 문제 해결

연결 문제가 발생했습니까? [Open WebUI Documentation](https://docs.openwebui.com/troubleshooting/)에서 해결 방법을 찾을 수 있습니다. 추가 지원과 활발한 커뮤니티에 참여하려면 [Open WebUI Discord](https://discord.gg/5rJgQTnV4s)를 방문하세요.

#### Open WebUI: 서버 연결 오류

연결 문제가 발생하는 경우, WebUI docker 컨테이너가 컨테이너 내부의 Ollama 서버 (127.0.0.1:11434 (host.docker.internal:11434))에 연결할 수 없기 때문인 경우가 많습니다. 이 문제를 해결하려면 docker 명령에 `--network=host` 플래그를 사용하세요. 포트가 3000에서 8080으로 변경되어 링크가 `http://localhost:8080`으로 변경됩니다.

**예제 Docker 명령**:

```bash
docker run -d --network=host -v open-webui:/app/backend/data -e OLLAMA_BASE_URL=http://127.0.0.1:11434 --name open-webui --restart always ghcr.io/open-webui/open-webui:main
```

### Docker 설치 최신 상태로 유지

로컬 Docker 설치를 최신 버전으로 업데이트하려면 [Watchtower](https://containrrr.dev/watchtower/)를 사용할 수 있습니다.

```bash
docker run --rm --volume /var/run/docker.sock:/var/run/docker.sock containrrr/watchtower --run-once open-webui
```

명령의 마지막 부분에서 `open-webui`를 컨테이너 이름으로 바꿉니다(다른 경우).

[Open WebUI Documentation](https://docs.openwebui.com/getting-started/updating)에서 업데이트 가이드를 확인하세요.

### Dev 브랜치 사용 🌙

> [!WARNING]
> `:dev` 브랜치에는 최신의 불안정한 기능과 변경 사항이 포함되어 있습니다. 버그나 불완전한 기능이 있을 수 있으므로 নিজ 책임하에 사용하세요.

최신 기능을 사용해보고 싶고 가끔 불안정해도 괜찮다면 다음과 같이 `:dev` 태그를 사용할 수 있습니다.

```bash
docker run -d -p 3000:8080 -v open-webui:/app/backend/data --name open-webui --add-host=host.docker.internal:host-gateway --restart always ghcr.io/open-webui/open-webui:dev
```

### 오프라인 모드

오프라인 환경에서 Open WebUI를 실행하는 경우 `HF_HUB_OFFLINE` 환경 변수를 `1`로 설정하여 인터넷에서 모델을 다운로드하려는 시도를 방지할 수 있습니다.

```bash
export HF_HUB_OFFLINE=1
```

## 다음은 무엇입니까? 🌟

[Open WebUI Documentation](https://docs.openwebui.com/roadmap/)의 로드맵에서 예정된 기능을 확인하세요.

## 라이선스 📜

이 프로젝트는 [BSD-3-Clause License](LICENSE)에 따라 라이선스가 부여됩니다. 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하세요. 📄

## 지원 💬

질문, 제안 또는 도움이 필요하면 문제를 제기하거나
[Open WebUI Discord community](https://discord.gg/5rJgQTnV4s)에 참여하여 저희와 연결하십시오! 🤝

## 스타 히스토리

<a href="https://star-history.com/#open-webui/open-webui&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=open-webui/open-webui&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=open-webui/open-webui&type=Date" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=open-webui/open-webui&type=Date" />
  </picture>
</a>

---

[Timothy Jaeryang Baek](https://github.com/tjbck) 제작 - Open WebUI를 함께 더욱 멋지게 만들어 갑시다! 💪
