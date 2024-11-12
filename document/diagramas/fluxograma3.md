          +------------------+
          |       Start      |
          +------------------+
                  |
                  |
                  v
          +-------------------+
          |  Sensores →       |
          |  DHT22, LDR,      |
          |  Botão F, Botão P |
          +-------------------+
                  |
                  |
                  v
          +-----------------+
          |  Leitura →      |
          |  Verificação    |
          +-----------------+
                  |
                  |
                  v
          +-------------------------------------------------+
          |  Decide →                                       |
          |  Umidade < 60%                                  |
          |  pH entre 6,0 e 8,0                             |
          |  Se pelo menos P ou K estiver presente          |
          +-------------------------------------------------+
                  |
                  |
                  v
          +-----------------+
          |  Liga Bomba →   |
          |  Desliga Bomba  |
          +-----------------+
                  |
                  |
                  v
          +-----------------+
          |  Liga LED →     |
          |  Desliga LED    |
          +-----------------+
                  |
                  |
                  v
          +-----------------+
          |       Fim       |
          +-----------------+