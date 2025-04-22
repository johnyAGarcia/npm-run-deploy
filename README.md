Visão Geral
Esta aplicação web permite setorizar clientes por região (Norte, Sul, Leste, Oeste) com subdivisões numéricas (1-4), visualizar em mapa, e calcular rotas otimizadas.
Funcionalidades Principais

    Importação de planilhas Excel com dados de clientes
    Geocodificação automática de endereços
    Setorização por região (Norte, Sul, Leste, Oeste) com subdivisões numéricas (1-4)
    Visualização em mapa interativo com cores diferentes para cada região
    Seleção de até 8 clientes e visualização de rota otimizada
    Exportação de dados processados
    Interface responsiva para uso em dispositivos móveis e desktop

Tecnologias Utilizadas

    React.js para interface de usuário
    Redux para gerenciamento de estado
    Material-UI para componentes de interface
    Leaflet.js para mapas interativos
    SheetJS para processamento de arquivos Excel
    IndexedDB (via Dexie.js) para armazenamento local

Estrutura do Projeto

    /src/components: Componentes React da interface
    /src/services: Serviços de backend (geocodificação, setorização, rotas)
    /src/store: Gerenciamento de estado com Redux
    /src/hooks: Hooks personalizados para integração com serviços
    /src/pages: Páginas principais da aplicação

Documentação

    Manual do Usuário: Instruções detalhadas para uso da aplicação
    Guia de Implantação: Instruções para implantar a aplicação em produção

Instalação e Execução
Pré-requisitos

    Node.js 14.x ou superior
    NPM 6.x ou superior

Instalação
bash

# Instalar dependências
npm install

Execução em Desenvolvimento
bash

# Iniciar servidor de desenvolvimento
npm start

Compilação para Produção
bash

# Criar build otimizado
npm run build

Licença
Este projeto é licenciado sob a licença ISC.
