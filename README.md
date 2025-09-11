***Notas importantes sobre o cenpy***

A versão 1.0.1 oferecida oficialmente pelo pip possui uma imcompatibilidade ao chamar o método *s_join()* do GeoPandas dentro da lib do Cenpy.

Para corrigir esse erro, rode esses comandos com o venv ativado para instalar a lib com código corrigido:

```bash
pip uninstall cenpy
```

```bash
pip install git+https://github.com/cenpy-devs/cenpy.git
```