# Final Project - PHP

Descrição curta
Projeto final do curso que demonstra conhecimentos em PHP e MySQL, com funcionalidades básicas de CRUD e autenticação simples. Serve como portfólio para mostrar competências em backend com PHP e integração com base de dados.

Estado: Concluído / Demonstração académica

Tecnologias
- PHP 7.4+
- MySQL / MariaDB
- HTML5, CSS3, JavaScript (vanilla)
- (Opcional) Bootstrap para estilos

Demo / Screenshots
- Adiciona aqui screenshots na pasta /assets ou um link se fizeres deploy.

Requisitos
- PHP 7.4 ou superior
- MySQL 5.7 ou superior
- XAMPP / MAMP / LAMP ou servidor PHP local

Instalação e execução local
1. Clona o repositório:
   git clone https://github.com/Rui-Silva-code/Final-Project-PHP.git
2. Copia o ficheiro de configuração de exemplo e atualiza as credenciais:
   cp config.example.php config.php
   (edita config.php com as tuas credenciais locais)
3. Importa a base de dados de exemplo (se existir):
   mysql -u teu_user -p nome_da_bd < sql/example_db.sql
4. Corre o servidor local (ou usa XAMPP):
   php -S localhost:8000
   Abre http://localhost:8000

Funcionalidades implementadas
- Autenticação básica (login e logout)
- CRUD para a entidade principal (por exemplo, produtos ou posts)
- Validação simples no front-end e back-end
- Layout responsivo com Bootstrap (quando aplicável)

Limitações conhecidas
- Senhas podem não usar hashing seguro — melhorar com password_hash (bcrypt)
- Sem recuperação de password/rotas de admin avançadas
- Sem testes automatizados

Estrutura de ficheiros (resumo)
- /index.php (ponto de entrada)
- /config.example.php (modelo de configuração)
- /sql/ (dump/schema de exemplo)
- /assets/ (CSS, JS, imagens)
- /app/ ou /src/ (lógica PHP)

O que aprendi
- Integração PHP + MySQL com prepared statements
- Conceitos básicos de autenticação e gestão de sessões
- Organização de ficheiros para um projeto web simples

Próximos passos sugeridos
- Implementar hashing de passwords (password_hash)
- Remover credenciais do repositório e usar variáveis de ambiente
- Adicionar testes e CI

Licença
Este projeto está licenciado sob a MIT License — vê o ficheiro LICENSE.

Contacto
Rui Silva — https://github.com/Rui-Silva-code
