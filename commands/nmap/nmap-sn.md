# nmap -sn

📌 **Descrição**  
Executa uma varredura do tipo *ping scan*, que serve para descobrir quais hosts (dispositivos) estão ativos em uma rede.  
Este modo **não escaneia portas**, apenas verifica se o host responde a ping (ou outros métodos de detecção).

---

## 💻 Sintaxe

```bash
nmap -sn <IP-OU-INTERVALO>

Exemplo: nmap -sn 192.168.0.0/24


* Dicas e Observações


Útil para mapear rapidamente quem está conectado à sua rede local.

Pode ser combinado com -v para mais detalhes (modo verboso).

Não requer privilégios de root na maioria dos sistemas.

Equivalente ao comando antigo: ping sweep.





Data: 14-04-2025
