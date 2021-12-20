# VMware SNMP ESXi 5.1

<img src="https://assets.zabbix.com/img/tmp/logo/logo_bad_example.png" alt="logo">

> Template do Zabbix para gerenciamento VMware através de SNMP e SSH, testado em Ambiente Zabbix 6.0.0 Beta 1

### Ajustes e melhorias

O projeto ainda está em desenvolvimento e as próximas atualizações serão voltadas nas seguintes tarefas:

- [x] Regras de Descoberta
- [x] Armazenamento
- [x] Rede
- [ ] Hardware
- [ ] + Trigguer

## 💻 Pré-requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:

* Versão do Zabbix `5.4 ou 6.0`
* VMware com SNMP habilitado `ESXi 5.1 ou Superior`.

## 🚀 Instalando

Para instalar o template, siga estas etapas:

Zabbix:
```
https://www.zabbix.com/documentation/current/pt/manual/xml_export_import
```

ESXi:
```
https://docs.vmware.com/br/VMware-vSphere/7.0/com.vmware.vsphere.monitoring.doc/GUID-8EF36D7D-59B6-4C74-B1AA-4A9D18AB6250.html
```

## ☕ Configurações

Para usar o template, siga estas etapas:

```
Adicione o host com o template VMware SNMP ESXi localizado em Templates/Applications e adicione as informações de SSH nas Macros
{$SSH_IP} - IP SSH
{$SSH_PASS} - Senha SSH
{$SSH_PORT} - Porta SSH
{$SSH_USER} - Usuário SSH
```

## 📝 Licença

Esse projeto está sob licença. Veja o arquivo [LICENÇA](LICENSE.md) para mais detalhes.
