import requests
incnpjbusca=input()
url = "https://www.receitaws.com.br/v1/cnpj/"+incnpjbusca
response = requests.get(url)
print(f' Response status code:{response.status_code}')
if response.status_code == 200:
    data = response.json()
    print(data)
else:
    print(f"Erro: {response.status_code}")
