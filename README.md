# An-lise-de-Dados
import random 
import numpy as np

Class RoboExplorador:
   def__init__(self, x, y):
       self.x = x
       self.y =y
       self.dados_sensoriais = []

def coletar_dados(self):
# Simula dados sensoriais aleatórios
distância = random.randint(1,10)
luz = random.randint(0, 100)
self.dados_sensoriais.append([distancia, luz])

def analisar_dados(self):
    # converte dados para array numpy para facilitar a análise 
    dados = np.array(self.dados_sensoriais)
    
  # Calcula estatísticas descritivas
  media_distancia = np.mean(dados[:, 0])
  media_luz = np.mean(dados[:, 1])

  # Simula tomada de decisão com base nos dados
  if media_distancia <5: 
     print("obstáculo próximo! Mudando de direção.")
   elif media_luz > 50: 
     print("Área iluminada! Avançando.")
   else: 
     print("Explorando a área.")

def mover(self, dx, dy):
    self.x += dx
    self.y += dy

# Cria o robô
robo = RoboExplorador(0, 0)

# Simula exploração
for_in range(10):
    robo.coletar_dados()
    robo.analisar_dados()
    robo.mover(random.randint(-1, 1), random.randint(-1, 1)) 

    









    
    

