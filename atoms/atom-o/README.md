# Oxigênio - O

O Oxigênio (O) é um elemento químico essencial para a vida na Terra, sendo fundamental para os processos de respiração e combustão. É o **elemento químico de número atômico 8** e faz parte dos gases mais abundantes na atmosfera.

## Estrutura

```js
module.exports = { 
  simbolo: 'O', 
  nome: {
    'pt-br': 'Oxigênio',
    'en': 'Oxygen',
  },
  familia: [
    {
      tipo: 'Coluna',
      valor: '16'
    }, 
    {
      tipo: 'Grupo',
      valor: '6A'
    }, 
    {
      tipo: 'descritivo',
      valor: 'Sem família'
    }
  ],
  periodo: 2, 
  massaAtomica: 15.999,
  numero: {
    eletrons: 8,
    neutrons: 8,
    protons: 8
  },
  distribuicaoEletronica: {
    k: [
      {
        subnivel: 's',
        eletrons: 2
      }
    ],
    l: [
      {
        subnivel: 's',
        eletrons: 2
      },
      {
        subnivel: 'p',
        eletrons: 4
      }
    ],
    m: [
      {
        subnivel: 's',
        eletrons: 0
      }
    ],
    n: [
      {
        subnivel: 's',
        eletrons: 0
      }
    ],
    o: [
      {
        subnivel: 's',
        eletrons: 0
      }
    ],
    p: [
      {
        subnivel: 's',
        eletrons: 0
      }
    ],
    q: [
      {
        subnivel: 's',
        eletrons: 0
      }
    ],
  },
  propriedades: {
    fisicas: [
      {   
        nome: 'Densidade',
        valor: 0.001429,
        unidade: 'kg/m3'
      },
      {   
        nome: 'estadodaMateria',
        valor: 'Gasoso' 
      },
      {   
        nome: 'raioAtomico',
        valor: 60,
      }
    ],
    quimicas: [ 
      require('property-estado-oxidacao-o'),
      require('property-estrutura-cristalina-o'),
      require('property-eletronegatividade-de-pauling-o'),
      {   
        nome: 'raioCovalente',
        valor: 60,
        unidade: require('unity-pm').unidade
      },
      {   
        nome: 'raioVanderWaals',
        valor: 152, 
        unidade: require('unity-pm').unidade
      },
      {   
        nome: 'entalpiadevaporizacao',
        valor: 0.218,
        unidade: require('unity-kjXmol-1').unidade
      },
      {   
        nome: 'calorEspecífico',
        valor: 918, 
        unidade: 'J/(kg·K)'
      },
      {   
        nome: 'condutividadeEletrica',
        valor: 0, 
        unidade: 'S/m'
      },
      {
        nome: 'condutividadeTermica',
        valor: 0.025,
        unidade: 'W/(m·K)'
      } 
    ]
  }
}
