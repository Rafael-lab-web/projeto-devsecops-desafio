# Desafio DevSecOps — Gerenciador de Tarefas

## Sobre o Projeto
Este repositório faz parte do desafio prático do módulo de DevSecOps da ADA Tech.
Você receberá este projeto com vulnerabilidades propositais e uma pipeline incompleta.
Seu objetivo é **implementar a pipeline de segurança** e **corrigir as vulnerabilidades**.

## Estado atual
A pipeline está **incompleta**. Os steps de segurança precisam ser implementados por você.

## Sua missão
1. Implementar os steps de segurança no `pipeline.yml`
2. Fazer a pipeline **quebrar** ao detectar os problemas
3. Corrigir as vulnerabilidades encontradas
4. Fazer a pipeline **passar** com tudo verde ✅
5. Documentar o funcionamento da pipeline neste README

## O que implementar
- [ ] Secrets Scanning com **Gitleaks**
- [ ] SAST com **Semgrep**
- [ ] SCA com **Grype**
- [ ] Deploy com **GitHub Pages**

## Como a pipeline funciona
> Secrets: verifica se tem credenciais visíveis. Ele é importante para evitar que dados confidenciais sejam vazados.
SAST: busca vulnerabilidades no código-fonte. É importante para detectar falhas ainda no desenvolvimento, reduzindo custo e tempo de correção.
SCA: Examina bibliotecas e dependências externas usadas no projeto, verificando se possuem vulnerabilidades. É importante porque o ajuda a manter o ecossistema seguro.
Deploy: garante que só código seguro chegue à produção. É importante por que o deploy é o ponto final do pipeline. Condicionar o deploy à aprovação dos steps de segurança evita que código inseguro seja publicado.


## URL de Produção
> https://rafael-lab-web.github.io/projeto-devsecops-desafio/
