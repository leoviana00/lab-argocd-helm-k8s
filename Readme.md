
<h1 align="center">Argocd</h1>

<p align="center">
  <img alt="Kustomize" src="https://img.shields.io/static/v1?label=K8S&message=Argocd&color=8257E5&labelColor=000000"  />
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000">
</p>

<p align="center">
  <img alt="k8s" src="images/argo.png">
</p>

## 🌱 Project
- Implantando argocd com helm 

## ✨ Ferramentas utilizadas

- Helm
- Kubernetes
- Argocd
- Docker
- Haproxy
- Docker Compose
- Shell Script

## 🚀 Etapas

- [x] Ter um cluster kubernetes
- [x] Instalação do Istio
- [x] Instalação do Helm
- [x] Addicionar Helm Chart do Argo
  - [x] Criar um values personalizado 
  - [x] Criar namespace
  - [x] Habilitar istio-injection no namespace do argo
  - [x] Criar gateway e virtualservice para acesso externo
- [x] Subir balanceador externo
  - [x] Configuração de acl e backend para o argo no balanceador

## 📄 Licença
Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

