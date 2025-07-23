
---

## 🛠️ Trabalhos Desenvolvidos

### 📄 Instalação I – Servidor Web e NTP

- Sincronização de hora entre VMs utilizando **Chrony**
- Instalação e configuração do **Apache2**
- Ativação do **SSL** (HTTPS)

> Ver detalhes no relatório: `relatorio_instalacao.pdf`

---

### 📄 Instalação II – FTP + DNS

- Instalação do servidor **vsftpd** (FTP)
- Configuração de **bind9** como servidor DNS interno
- Criação do domínio fictício: `baixaeconfia.grupow.br`
- Encaminhamento de requisições externas via DNS (Google DNS)

> Ver detalhes no relatório: `Relatorio_Servicos_Rede_GrupW.pdf`

---

## 🧪 Testes Realizados

- Acesso FTP via linha de comando (upload/download)
- Testes de `ping` nos domínios internos e externos:
  - `ping www.baixaeconfia.grupow.br`
  - `ping ftp.baixaeconfia.grupow.br`
  - `ping www.uol.com.br`
- Verificação de sincronização de hora com NTP

---

## 🖧 Simulações no Cisco Packet Tracer

As simulações em `.pkt` representam a topologia utilizada e os serviços configurados nas VMs.

> Arquivos:
> - `TrabalhoPacketTracer3-Grupo-W.pkt`
> - `trabalho-packet-tracer.pkt`

---

## 🔗 Referências

- Documentação oficial do [vsftpd](https://security.appspot.com/vsftpd.html)
- [Apache2 Ubuntu Documentation](https://ubuntu.com/server/docs/web-servers-apache)
- [BIND9 DNS Server](https://wiki.debian.org/Bind9)
- [Chrony NTP](https://chrony.tuxfamily.org/)
