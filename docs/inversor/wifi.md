# 🌐 Como reconectar o inversor ao Wi-Fi

Se você trocou de operadora de internet, mudou o roteador de lugar ou alterou a senha do seu Wi-Fi, o inversor perderá a conexão. Isso significa que ele **continua gerando energia normalmente**, mas para de enviar os gráficos para o seu aplicativo.

Siga as orientações abaixo para restabelecer a conexão.

---

## ⚠️ A Regra de Ouro: Atenção ao 5G!

Os dataloggers (as "antenas" USB conectadas embaixo do inversor) utilizam uma tecnologia de longo alcance e **só funcionam em redes Wi-Fi de 2.4 GHz**. 

* Se a sua rede tem nomes como "MinhaCasa_5G", **não escolha essa opção**. 
* Conecte o seu celular na rede normal (sem o "5G" no nome) antes de começar o procedimento. Caso o seu roteador novo não tenha a rede 2.4 GHz ativada, solicite ao seu provedor de internet a ativação.

---

## 📱 Passo a Passo Geral da Reconexão

Antes de abrir o aplicativo, prepare-se:
1. Vá para perto do inversor (onde o sinal do roteador precisa chegar bem).
2. Tenha a **nova senha** do Wi-Fi anotada.
3. Certifique-se de que o Bluetooth e o GPS (Localização) do seu celular estão ativados, pois os aplicativos precisam disso para encontrar a antena.

### Como fazer nos principais aplicativos:

#### ⚪ ABB / FIMER (Via Navegador de Internet)
*Muitos inversores ABB/FIMER são configurados diretamente pelo navegador, sem precisar de aplicativo.*
1. Vá nas configurações de Wi-Fi do celular e conecte-se à rede do inversor (o nome será **ABB-** ou **FIMER-** seguido de números).
2. Abra o navegador do celular (Chrome, Safari, etc.) e digite o endereço: **`192.168.117.1`**.
3. Faça o login como usuário ou convidado (caso peça senha e você não tenha, consulte nosso suporte).
4. No menu lateral da página, vá em **Configurações** (Settings) > **Configurações de Rede** > **Wireless**.
5. Selecione a sua rede de casa, insira a nova senha e salve para reiniciar a conexão.

#### 🔴 Canadian Solar (App CSI Solar / Solarman)
1. Na tela inicial, vá até a aba **Dispositivos**.
2. Toque no **Datalogger** (Logger).
3. Selecione a opção **Configuração de Rede** (Network Configuration).
4. O app guiará você para se conectar à rede do inversor temporariamente (AP Mode) ou fará a configuração via Bluetooth.
5. Selecione a rede da sua casa, insira a senha e aguarde a luz azul do datalogger parar de piscar.

#### 🟢 Growatt (App ShinePhone)
1. Abra o aplicativo e faça login.
2. Na aba **Planta**, toque em cima do nome da sua usina.
3. Vá na lista de dispositivos e clique no número de série do seu **Datalogger**.
4. Selecione a opção **Configurar Wi-Fi** (ou *Configure Datalogger*).
5. O aplicativo pedirá para ler o **QR Code** ou o código de barras impresso na antena do inversor.
6. Confirme o nome da sua rede de casa, digite a senha nova e aguarde a configuração chegar a 100%.

#### 🔵 WEG / FoxESS (App FoxCloud)
1. Abra o aplicativo e vá até a aba **Meu** (ou Perfil).
2. Selecione **Configuração de Wi-Fi**.
3. O aplicativo pedirá para você se conectar ao sinal que a própria antena do inversor emite (geralmente uma rede Wi-Fi que começa com o nome *W-* seguido de números).
4. Após se conectar na antena, volte ao aplicativo e escolha a rede Wi-Fi da sua casa na lista.
5. Digite a senha e confirme.

#### 🔵 Hoymiles (App S-Miles End User)
*Nota: A Hoymiles usa microinversores, então você fará essa configuração na **DTU** (aquela caixinha ou antena transmissora que fica próxima ao roteador ou no quadro de luz).*
1. No seu celular, conecte-se à rede Wi-Fi gerada pela DTU (o nome geralmente começa com **DTUBI-** seguido do número de série).
2. Abra o aplicativo **S-Miles End User**.
3. No menu inferior, vá na aba **O&M** (Operação e Manutenção).
4. Clique em **Configuração de Rede**.
5. Selecione o Wi-Fi da sua residência, digite a senha e clique em enviar. A DTU vai reiniciar já conectada na rede nova.

#### 🔴 Huawei (App FusionSolar)
1. Abra o aplicativo **FusionSolar**. Não faça login. Na tela inicial, toque nos três pontinhos no canto superior e escolha **Comissionamento de Dispositivo**.
2. Escaneie o QR Code que fica na lateral do inversor.
3. O app vai pedir para conectar ao Wi-Fi do inversor (a rede costuma se chamar *SUN2000...* e a senha padrão é **Changeme**).
4. No menu principal de configuração, acesse **Configurações** > **Configuração de Comunicação** > **Configurações do Roteador**.
5. Localize sua nova rede de internet, insira a senha e aplique.

#### 🟢 Hypontech (App HiCloud)
1. Antes de abrir o app, vá nas configurações de Wi-Fi do seu celular e conecte-se à rede gerada pelo datalogger (o nome geralmente começa com **EAP_**).
2. Abra o aplicativo **HiCloud**.
3. Na tela de login (sem precisar entrar na conta), procure a opção **Configuração Local** (ou *Wi-Fi Config*).
4. O app vai escanear as redes em volta. Selecione a rede 2.4 GHz da sua casa, digite a senha e confirme.

#### 🟠 Livoltek (App My Livoltek)
1. Ligue o Bluetooth e o GPS do seu celular e fique próximo ao inversor.
2. Abra o aplicativo **My Livoltek** e faça login na sua conta.
3. Vá até a aba **Eu** (no canto inferior direito) e selecione **Configuração de Bluetooth/Wi-Fi**.
4. O app localizará o inversor via Bluetooth. Confirme a conexão.
5. Na tela seguinte, escolha a opção de buscar as redes de internet locais, selecione a da sua casa e atualize a senha.

#### 🟣 Solplanet (App Solplanet / AiSWEI)
1. Abra o aplicativo e faça login.
2. Acesse a aba **Planta** ou **Dispositivos** e clique em **Configuração de Rede** (ou *Network Config*).
3. O aplicativo pedirá que você conecte o celular temporariamente à rede Wi-Fi que o próprio inversor emite (geralmente começa com as letras **SG**).
4. Volte ao aplicativo, escolha a rede Wi-Fi da sua casa na lista, digite a nova senha e aguarde a luz azul/verde estabilizar.

---

> 💡 **Ainda não conseguiu?**
> Se a configuração falhar no meio, tente desligar a chave do inversor, aguardar 1 minuto, ligar novamente e tentar refazer os passos do zero. <!-- Caso o problema persista, [clique aqui para falar com nosso suporte técnico](link-do-seu-whatsapp). -->