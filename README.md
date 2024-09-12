# .github

# Fase 3

1. Implementar um API Gateway e um function serverless para autenticar o cliente com base no CPF
    - Integrar ao sistema de autenticação para identificar o cliente.

2. Implementar as melhores práticas de CI/CD para a aplicação, segregando os códigos em repositórios, por exemplo:
    - 1 repositório para o Lambda.
    - 1 repositório para sua infra Kubernetes com Terraform.
    - 1 repositório para sua infra banco de dados gerenciáveis com Terraform.
    - 1 repositório para sua aplicação que é executada no Kubernetes.

3. Os repositórios devem fazer deploy automatizado na conta da nuvem utilizando actions. As branchs main/master devem ser protegidas, não permitindo commits direto. Sempre utilize pull request.

4. Melhorar a estrutura do banco de dados escolhido, documentar seguindo os padrões de modelagem de dados e justificar a escolha do banco de dados.