# Documentação de Implantação de WordPress no HostGator
### Pré-requisitos
1. Conta ativa no HostGator com um plano de hospedagem.
2. Domínio registrado e configurado no HostGator.
3. Acesso ao cPanel (painel de controle do HostGator).

### Passo a Passo
1. Acesse o cPanel no HostGator
- Faça login na sua conta [HostGator](https://financeiro.hostgator.com.br/).
- Utilize o dominio principal ou crie um novo dominio.
- No painel da conta, localize e clique em cPanel.

2. Localize o Instalador de WordPress
- No cPanel, role até a seção Softaculous Apps Installer.
- Clique em instalar WordPress.

3. Configuração da Instalação:
- Escolha o domínio em que deseja instalar o WordPress. Exemplo: testando.laboware.com.br.
- Certifique-se de remover diretórios do campo Diretório.

4. Configure os detalhes do site:
- Nome do site: Insira o nome do site (ex:"laboware").
- Descrição do site: Insira uma breve descrição (ex:"Um site sobre serviços de TI").
- Admin Username: Defina um nome de usuário para o administrador (evite usar "admin" por segurança).
- Admin Password: Crie uma senha forte.
- Admin Email: Insira um e-mail válido para o administrador.

5. Finalize a Instalação
- Clique no botão Instalar.
- Aguarde o progresso da instalação (geralmente leva menos de 2 minutos).
- Quando concluído, o sistema exibirá a URL do site e a URL de acesso ao painel administrativo:
- URL do site: https://seusite.com.br
- Admin URL: https://seusite.com.br/wp-admin

### Configuração Inicial no WordPress
Acesse o painel administrativo do WordPress (/wp-admin) com o usuário e senha configurados.
#### No painel:
- Na aba de *Apresentação* podemos escolher os temas para o site e personalizar conforme necessario
- Na aba de *Plugins*  podemos instalar diversos plugins que ajudam a melhorar o desempenho do site 

#### Teste e validação 
- Verifique se o site está funcionando corretamente:
- Acesse a URL principal do site.
- Realize testes básicos, como navegar pelas páginas e testar formulários.

#### Manutenção e Segurança
- Backup Automático: Configure backups regulares no HostGator ou instale o plugin UpdraftPlus.
- Segurança: Instale o plugin Wordfence Security para proteger o site.
