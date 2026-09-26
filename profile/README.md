<h1 align="center">
  Studies
</h1>

<p align="center">
  <b>Estudos, labs e planos para certificações.</b><br>
  Cloud, Kubernetes, infraestrutura como código e IA, estudados na prática.
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/studies-org/studies-cert-kubestronaut/main/docs/demo.webp" alt="Mission Control do Kubestronaut: constelação 3D das certificações, pomodoro e estatísticas" />
</p>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=aws,azure,kubernetes,terraform,docker,linux,flask,mysql,nextjs,threejs,fastapi,md" alt="Stacks" />
  </a>
</p>

## O que tem aqui

Cada repositório é um estudo com material próprio, exercícios e, quando faz sentido, uma aplicação ou infraestrutura de verdade para praticar o que está sendo estudado.

### Certificações

| Repositório | O que é |
|---|---|
| [studies-cert-kubestronaut](https://github.com/studies-org/studies-cert-kubestronaut) | Plano para as **5 certificações Kubernetes da CNCF** (KCNA, KCSA, CKA, CKAD e CKS) e o **Mission Control**, um painel com constelação 3D, pomodoro e estatísticas |
| [studies-cert-aws-ai-practitioner](https://github.com/studies-org/studies-cert-aws-ai-practitioner) | Plano para a **AWS Certified AI Practitioner (AIF-C01)**: 57 aulas, 96 exercícios, placar por seção e tutor no Claude Code |

### Labs

| Repositório | O que é |
|---|---|
| [studies-lab-terraform-modules](https://github.com/studies-org/studies-lab-terraform-modules) | Biblioteca de **módulos Terraform** para a AWS, feita em dupla, começando pelo `infra-base` (VPC, subnet pública, Internet Gateway e route table) |
| [studies-lab-multicloud-terraform](https://github.com/studies-org/studies-lab-multicloud-terraform) | Site estático atrás de **load balancer na AWS e na Azure**, com módulos Terraform simétricos nas duas nuvens e simulação local |
| [studies-lab-docker-microservices](https://github.com/studies-org/studies-lab-docker-microservices) | **Microserviços Flask** de itens, lojas, pedidos e pagamentos com **Docker Compose**, um MySQL por serviço e painel web |

### Estudos

| Repositório | O que é |
|---|---|
| [studies-terraform-modules](https://github.com/studies-org/studies-terraform-modules) | **Módulo de EC2** reutilizável (security group, tags padronizadas e Apache via cloud-init), instanciado quatro vezes com `for_each` |

## Destaques

<table>
  <tr>
    <td align="center" width="50%">
      <img src="https://raw.githubusercontent.com/studies-org/studies-lab-terraform-modules/main/docs/arch.gif" alt="Módulo infra-base: VPC, subnet pública, Internet Gateway e route table" /><br>
      <sub><b>Lab Terraform</b> · módulo infra-base</sub>
    </td>
    <td align="center" width="50%">
      <img src="https://raw.githubusercontent.com/studies-org/studies-cert-aws-ai-practitioner/main/docs/study-flow.gif" alt="Fluxo de estudo: aula, exercícios, correção pelo tutor, placar e exame" /><br>
      <sub><b>AWS AI Practitioner</b> · fluxo de estudo</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="https://raw.githubusercontent.com/studies-org/studies-lab-multicloud-terraform/main/docs/arch.gif" alt="Site estático com load balancer na AWS e na Azure provisionado por Terraform" /><br>
      <sub><b>Lab multicloud</b> · AWS e Azure</sub>
    </td>
    <td align="center" width="50%">
      <img src="https://raw.githubusercontent.com/studies-org/studies-lab-docker-microservices/main/docs/arch.gif" alt="Painel nginx, quatro microserviços Flask e um MySQL por serviço" /><br>
      <sub><b>Lab microserviços</b> · Docker Compose</sub>
    </td>
  </tr>
</table>

## Padrão de nomenclatura

| Tipo | Padrão |
|------|--------|
| Certificação | `studies-cert-<certificação>` |
| Lab | `studies-lab-<tema>` |
| Estudo | `studies-<tema>` |

## Autor

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/willtechdev">
        <img src="https://github.com/willtechdev.png" width="100px;" alt="William Coelho"/><br>
        <sub><b>William Coelho</b></sub>
      </a>
    </td>
  </tr>
</table>
