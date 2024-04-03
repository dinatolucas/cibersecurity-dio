# Phishing para Captura de Senhas

Este é um guia para configurar um ataque de phishing destinado a capturar senhas usando ferramentas disponíveis no Kali Linux.

## Ferramentas

- Kali Linux
- setoolkit

## Configurando o Phishing no Kali Linux

1. **Acesso root**: Abra um terminal e torne-se superusuário executando o seguinte comando:
    ```
    sudo su
    ```

2. **Iniciando o setoolkit**: No terminal, inicie o setoolkit executando o seguinte comando:
    ```
    setoolkit
    ```

3. **Tipo de ataque**: Escolha "Social-Engineering Attacks" no menu.

4. **Vetor de ataque**: Selecione "Web Site Attack Vectors".

5. **Método de ataque**: Escolha "Credential Harvester Attack Method".

6. **Método de ataque**: Selecione "Site Cloner".

7. **Obtendo o endereço da máquina**: No terminal, execute o comando `ifconfig` para obter o endereço IP da sua máquina.

8. **URL para clone**: Use o endereço IP obtido e configure-o para o site do Facebook, por exemplo:
    ```
    http://<seu_endereco_ip>
    ```

9. **Resultados**: Após configurar o phishing, aguarde que as vítimas acessem o site clonado e forneçam suas credenciais. As credenciais capturadas serão armazenadas para análise posterior.
    
![Captura de tela de 2024-04-03 10-49-17](https://github.com/dinatolucas/cibersecurity-dio/assets/83898401/b0adc9d6-4e8e-4746-9ca9-5a24ac8f3107)

**Nota**: O uso de técnicas de phishing é ilegal e antiético se realizado sem consentimento explícito. Este guia é fornecido apenas para fins educacionais e de conscientização sobre segurança cibernética. Sempre obtenha permissão antes de realizar testes de segurança em sistemas e redes que não são de sua propriedade.
