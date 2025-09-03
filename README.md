# Jurandir Aparecido dos Santos Sobrinho da Cruz
**Desenvolvedor Web | Infra & DevOps (PHP · Laravel · Docker · Linux)**

[![Website](https://img.shields.io/badge/Website-portfolio-informational?style=for-the-badge)](https://seu-site-aqui.com) 
[![Email](https://img.shields.io/badge/Contato-jurandir%40seuemail.com-blue?style=for-the-badge&logo=gmail)](mailto:jurandir@seuemail.com) 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Perfil-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/seu-perfil) 
[![Disponível para trabalho](https://img.shields.io/badge/Disponível-Contratação-success?style=for-the-badge)]

---

## Sobre mim
Sou estudante de **Análise e Desenvolvimento de Sistemas (IFPR)** com experiência prática em desenvolvimento backend (PHP/Laravel) e infraestrutura T.I. Tenho histórico em projetos de e-commerce e dashboards, além de atividades de suporte e operação de sistemas (emissão de NFP - Paraná). Busco oportunidades para aplicar boas práticas de engenharia, automação e arquitetura simples e escalável.

**Diferenciais:**
- Experiência com infraestrutura (TrueNAS, Windows Server 2016, VMs, manutenção de hardware).
- Forte base em PHP e Laravel + integração com front (Blade, AJAX).
- Experiência com Docker, Git, Composer e deploys em ambientes Linux.
- Projetos práticos: e-commerce (peças de skate/roupas) com parcelamento; dashboard de suporte; sistema de autoatendimento em React com pagamentos via PIX.

---

## Tech Stack & Ferramentas
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Composer](https://img.shields.io/badge/Composer-8892BF?style=for-the-badge&logo=composer&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![VSCode](https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

---

## Experiência & Realizações
- **Estágio em T.I. — Prefeitura de Umuarama** — Suporte e manutenção, implantação de rotinas de backup e gestão de pequenos servidores.
- **Operador do sistema NFP - PR** — Emissão e atendimento operacional de notas fiscais do produtor.
- **Desenvolvimento de projetos pessoais**: E-commerce (peças de skate e roupas) com checkout parcelado; dashboard de suporte com Laravel + AJAX; sistema de autoatendimento em React (simulação de compra e integração PIX).
- **Formação**: Curso técnico/graduação em Análise e Desenvolvimento de Sistemas (IFPR — Campus Umuarama).

---

## Projetos em destaque
> Repositórios pinados no perfil são as primeiras impressões que recrutadores veem. Mantenha READMEs individuais explicativos, badges de build/coverage e um deploy (se aplicável).

- **Brooklyn** — Repositório principal (ex: loja e-commerce).  
  `Descrição curta:` E-commerce para venda de peças de skate e roupas — backend em Laravel, integração de pagamentos e verificação de estoque por tamanho.

- **Caderno de Erros** — Sistema para estudos, com correção e sistema de peso por questão (Laravel + Blade + AJAX).
---

## Como rodar (exemplo Laravel)
```bash
# clonar
git clone https://github.com/jurandircod/nome-do-repo.git
cd nome-do-repo

# backend
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed

# se usar frontend node
npm install
npm run dev

# rodar localmente
php artisan serve
