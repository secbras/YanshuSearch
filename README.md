
<img src="https://github.com/secbras/YanshuSearch/blob/main/imagens/yanshu.png?raw=true" alt="Yanshu Search">

<h1>Yanshu Search</h1>

---

O Yanshu Search é uma ferramenta avançada de varredura passiva de subdomínios desenvolvida pela SecBras Research. Ela realiza buscas simultâneas em diversas fontes públicas, como motores de busca, certificados SSL, DNS passivos, serviços de reputação e inteligência como VirusTotal, ThreatCrowd e muito mais.

A interface exibe um banner animado e mensagens coloridas para melhor acompanhamento em tempo real, tornando a experiência mais interativa e clara. A utilização de **multi-threading** garante desempenho ágil e eficiente.

## Funcionalidades:

- Busca simultânea em mais de 10 fontes públicas
- Extração de subdomínios via regex
- Resultados coloridos no terminal com `colorama`
- Relatório final com número total de subdomínios únicos encontrados
- Interface simples com prompt interativo

## Instalação:

```bash
git clone https://github.com/secbras/YanshuSearch
cd YanshuSearch
pip install -r requirements.txt
```

## Uso:

```bash
python yanshu-search.py
```

Ao executar, digite o domínio que deseja analisar, como `example.com`.

## Fontes utilizadas:

- Google, Bing, Yahoo, Baidu, Ask
- Certificados SSL
- PassiveDNS
- VirusTotal
- ThreatCrowd
- Shodan
- Censys
- Netcraft
- SecurityTrails
- DNSDumpster (suporte limitado)

## Contribuições:

Contribuições são muito bem-vindas! Sinta-se livre para abrir uma **Issue** ou enviar um **Pull Request** com melhorias, correções ou novas ideias.

## Licença:

Este projeto está licenciado sob a [MIT License](https://opensource.org/licenses/MIT).

---

Utilize o Subdomain Finder para obter uma visão detalhada da superfície de ataque de um domínio, identificando subdomínios expostos com rapidez e precisão.

**Desenvolvido pela SecBras Research**
