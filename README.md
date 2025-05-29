1. Criar um repositório GitHub e clonar localmente. - OK
2. Executar os testes com pytest e corrigir o erro na aplicação. -OK
3. Fazer commits semânticos para cada alteração. - OK
4. Criar um workflow GitHub Actions que: 
○ Execute os testes com pytest. - OK
○ Crie uma imagem Docker e publique no DockerHub. - OK
5. Criar configuração de Deployment e Service no Kubernetes, usando Kustomize. - OK
6. Ajustar o workflow de CI/CD para:
○ Atualizar o kustomization.yaml com a imagem gerada e versão. - OK
○ Fazer commit e push automático da alteração. - OK
7. Configurar um cluster local com Kind, com 3 nodes (sendo um control-plane). - OK
8. Instalar e configurar o ArgoCD. - OK
9. Criar um App no ArgoCD apontando para seu repositório e diretório de
configurações Kubernetes. - OK
10. Fazer a sincronização via ArgoCD e testar a aplicação com kubectl
port-forward. - OK
11. Fazer uma alteração no FastAPI, realizar o push e verificar se o ArgoCD detecta e
sincroniza corretamente - Erros abaixo

Erros:

![image](https://github.com/user-attachments/assets/ba904bb3-90cd-4a6d-928e-7c0e66066450)
![image](https://github.com/user-attachments/assets/c72f0635-43a6-4e19-b22b-acd7e054e9d4)
