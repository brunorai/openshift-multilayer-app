### Como utilizar:

#### Requisitos: 

Todos os comandos serão feitos no lab     virtual do Openshift, qual já tem as ferramentas necessárias (vim, git, oc, etc).


1. **Clone o repositório**: 

     ```bash
    git clone https://github.com/m-marcal/openshift-multilayer-app.git
    ```
2. **Faça login no OpenShift**: 

     ```bash
    oc login -u admin -p redhatocp https://api.ocp4.example.com:6443
    ```
3. **Crie um novo projeto no Openshift**: 

     ```bash
    oc new-project multilayer-app
    ```
4. **Crie os recursos do cluster definidos nos arquivos .yaml**: 

     ```bash
    oc apply -n multilayer-app -f wordpress/
    ```








