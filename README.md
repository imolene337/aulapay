# aulapay


# teste

# vai corinthians 

# yuri Alberto

import requests

reqUrl = "https://api.github.com/octocat"

headerList = {
    "Accept": "application/vnd.github.v3+json",  # Corrigido para a versão correta da API
    "User-Agent": "Thunder Client (https://www.thunderclient.com)",
    "X-GitHub-Api-Version": "2022-11-28"
}

payload = ""  # O payload geralmente é usado para enviar dados com a requisição, mas nesse caso não precisa ser alterado.

response = requests.get(reqUrl, headers=headerList)  # Usando requests.get para simplificar

print(response.text)
