
# Bobinadeira Automática Handmades

Projeto coletivo de bobinadeira automática com uso direcionado a bobinas para captadores e transformadores de tensão.

## Discussão

A discussão do projeto está centralizada no fórum [Handmades](http://www.handmades.com.br/forum/) tópico [Coil Winder](http://www.handmades.com.br/forum/index.php?topic=12323.0)

## Licença

GNU General Public License v3.0

**Características**
Pode copiar
Pode alterar
Tem que manter o código público
Tem que manter a mesma licença

## Versões

### Original

> Baseado no projeto [DIY-Arduino-based-Guitar-Pickup-Coil-Winder](https://github.com/sandy9159/DIY-Arduino-based-Guitar-Pickup-Coil-Winder)

- [x] Arduino uno ou compatível
- [x] Display HMI
- [ ] Display I2C


### Custo reduzido

> Substituição do display HMI por I2C e inclusão de controles

- [x] Arduino uno ou compatível
- [ ] Display HMI Nextion
- [x] Display I2C


### Hardcore

> Versão minimalista do arduino baseado no projeto [Arduino 100 Noção](https://garoa.net.br/wiki/Arduino_100_No%C3%A7%C3%A3o#Esquema_de_montagem_2)

- [ ] Arduino uno ou compatível
- [ ] Display HMI Nextion
- [x] Display I2C


## Características técnicas
### Motores
Para manter as facilidades das bibliotecas utilizadas no projeto inicial, é necessário o de motores de passo para o enrolador e controlador da guia.

Dado a limitação dos drivers sugerido, corrente e tensão máximas são **2,5A** e **45V** respectivamente.

#### Driver
O driver sugerido para todas as versões é o **[DRV8825](https://www.ti.com/lit/ds/symlink/drv8825.pdf?ts=1625675683245)** que conta com limitador de corrente ajustável e proteção contra superaquecimento.

**Tensão de operação**: 8,2V a 45V
**Corrente fornecida**: 2,5A por bobina com ventilação forçada (24V e 25°C)
**Resoluções de passo**: 6 (1/1, 1/2, 1/4, 1/8, 1/16, 1/32)



