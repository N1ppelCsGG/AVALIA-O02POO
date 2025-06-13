class Gerente_Administrativo(Empregados): #criamos uma classe concreta que herda da classe Abstrata
  hora = 28
  def mostrar_funçao(self): #Implementamos o metodo concreto
    print(" A Funçao do Gerente Administrativo é realizar a elaboração de relatórios," \
        " planejamento estratégico e garante" \
                " que as atividades sejam desenvolvidas de acordo com o planejado para atingir " \
                "os objetivos da empresa.") #Implementamos as regras de  negocio especificas da classe concreta
  def apresentar_cargo(self): #Implementamos o metodo concreto
    print("Gerente Administrativo") #Implementamos as regras de  negocio especificas da classe concreta

  def calcular_salario(self): #Implementamos o metodo concreto
    salario = (self.hora * 8) * 30 #Implementamos as regras de  negocio especificas da classe concreta
    print(f"O salario do Gerente Administrativo é R${salario}") #Implementamos as regras de  negocio especificas da classe concreta
  def local_de_almoço(self): #Implementamos o metodo concreto
     print("Local de almoço do Gerente Administratio é na Cozinha dos Chefes") #Implementamos as regras de  negocio especificas da classe concreta

  def uniformes(self): #Implementamos o metodo concreto
     print("O Gerente Administrativo usa Roupa Pessoal") #Implementamos as regras de  negocio especificas da classe concreta

         

class Empregado_Comum(Empregados): #criamos outra classe concreta que herda da classe Abstrata
  hora = 11
  def mostrar_funçao(self): #Implementamos o metodo concreto
        print("Realiza atividades específicas conforme sua área de atuação," \
        " como atendimento ao cliente, produção, vendas ou suporte administrativo.") #Implementamos as regras de 
                                                                                     #negocio especificas da classe concreta

  def apresentar_cargo(self): #Implementamos o metodo concreto
        print("Empregado Comum") #Implementamos as regras de 
                                 #negocio especificas da classe concreta


  def calcular_salario(self): #Implementamos o metodo concreto
    salario = (self.hora * 8) * 30 #Implementamos as regras de  negocio especificas da classe concreta
    print(f"O salario do Empregado comum é R${salario}") #Implementamos as regras de  negocio especificas da classe concreta

  def local_de_almoço(self): #Implementamos o metodo concreto
     print("Local de almoço do Empregado Comum é no refeitorio")#Implementamos as regras de  negocio especificas da classe concreta
  def uniformes(self):  #Implementamos o metodo concreto
     print("O Empregado Comum usa Uniforme Padrao da Empresa") #Implementamos as regras de  negocio especificas da classe concreta
           

    


        
        

   
