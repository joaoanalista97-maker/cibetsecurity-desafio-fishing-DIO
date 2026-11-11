# 🎣 Phishing para captura de senhas

> Este projeto tem como objetivo utilizar a ferramenta setoolkit para criar uma página falsa para captura de senhas, com fins educacionais e defensivos.

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![Licença](https://img.shields.io/badge/licença-MIT-blue)
![Plataforma](https://img.shields.io/badge/plataforma-Linux-green)

---

## 📌 Sobre o Projeto


Este projeto tem como objetivo estudar técnicas de phishing, auxiliando na conscientização e na defesa de usuários e organizações.

### 🎯 Objetivos

- Entender como funcionam os ataques de phishing
- Aplicar os conceitos aprendidos em um cenário real; 
- Documentar seu raciocínio técnico e decisões de forma clara e organizada; 
- Utilizar o GitHub como plataforma para versionamento e exposição do trabalho. 

> ⚠️ **Aviso:** Este projeto é destinado exclusivamente a **fins educacionais e defensivos**. Não utilize o conteúdo para atividades ilegais ou sem autorização.

---


## 🐧 Script Shell (Kali Linux)

### Requisitos

- Distribuição Linux Kali
- Bash 5.3.9
- Dependências: `setoolkit`

### Como executar

```bash
# Entrar em modo root
sudo su

# Executar ferramenta Setoolkit
setoolkit

#No menu que aparece selecionar a opção 1
1) Social-Engineering Attacks

#No menu seguinte selecionar opção 2
2) Website Attack Vectors

#No próximo Menu selecionar a opção 3
3) Credential Harvester Attack Method

#Logo após você escolher um site para clonar ou utilizar algum template existente.
#Para esse senário terei que optar por um template existente pois a rede em que estou possui IPS e está barrando a clonagem então tive que deixar a VMs fora da rede.
#Escolher Opção 1
1) Web Templates

#Em seguida você deve informar qual IP o servidor ira rodar. Por padrão o sistema já reconhece o IP da placa mas você pode configurar outro IP
set:webattack> IP address for the POST back in Harvester/Tabnabbing [10.0.2.15]: 192.168.70.20

#Depois você deve escolher entre os templates disponíveis que nesse caso iremos utilizar a página do Twitter.
3. Twitter

#Após processo acima a ferramenta ira subir um servidor com uma página falsa onde o usuário ira digitar as credenciais de acesso e o servidor ira capturar as informações em texto claro e mostrar no terminal.
```


---

## 🛠️ Ferramentas Utilizadas

| Ferramenta | Finalidade |
|------------|------------|
| `setoolkit` | Framework para realização de pentest |
| `Kali Linux` | Ambiente de testes |


---

## 📊 Resultados

<img width="737" height="159" alt="RESULTADO-PHISHING" src="https://github.com/user-attachments/assets/75a69b0c-c5db-40ef-875c-fead34161287" />

-Como podemos ver na imagem no teste realizado a página clonada capturou as credenciais de acesso e exibiu em texto claro.

## 🛡️ Boas Práticas de Prevenção

- Verifique sempre o remetente e o domínio do link antes de clicar
- Desconfie de mensagens com urgência excessiva
- Ative a autenticação em dois fatores (2FA)
- Mantenha sistemas e antivírus atualizados
- Reporte e-mails suspeitos ao setor de segurança

---

## 🤝 Contribuições

Contribuições são bem-vindas! Faça um *fork* do projeto, crie uma branch e abra um *Pull Request*.

---

## 📬 Informações de Contato

| | |
|---|---|
| **Nome** | João Vitor dos Santos Ferreira |
| **E-mail** | joao.analista97@gmail.com |
| **LinkedIn** | [linkedin/in/joão-vitor-dos-santos-ferreira-015064186](https://www.linkedin.com/in/joão-vitor-dos-santos-ferreira-015064186/) |
| **GitHub** | [github.com/joaoanalista97-maker](https://github.com/joaoanalista97-maker) |

---

## 📄 Licença

Este projeto está sob a licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.
