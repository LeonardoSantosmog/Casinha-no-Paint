# 🖌️ Automação com PyAutoGUI - Desenhando no Paint

Este projeto utiliza a biblioteca [PyAutoGUI](https://pyautogui.readthedocs.io/en/latest/) para automatizar a abertura do **Paint** no Windows e desenhar figuras de forma programada.

---

## 🚀 Como funciona
O script realiza as seguintes ações automaticamente:
1. Abre o menu iniciar (`Win`).
2. Digita **paint** e abre o aplicativo.
3. Clica em posições específicas da tela.
4. Usa `dragRel` para desenhar formas e padrões geométricos.

Exemplo de ações do script:
- Desenha quadrados e linhas no Paint.
- Clica em ferramentas e cores.
- Cria padrões geométricos usando coordenadas.

---

## 📂 Estrutura
- `main.py`: Código principal de automação.
- `README.md`: Documentação do projeto.

---

## 🔧 Requisitos
Antes de rodar o projeto, instale as dependências:

```bash
pip install pyautogui

---------------------------------------------------------------------

import pyautogui

pyautogui.press('win')
pyautogui.sleep(1)
pyautogui.write('paint')
pyautogui.sleep(1)
pyautogui.press('enter')
pyautogui.sleep(1)
pyautogui.click(600,600)
pyautogui.sleep(1)
pyautogui.dragRel(200,0)
pyautogui.sleep(1)
pyautogui.dragRel(0,200)
pyautogui.sleep(1)
pyautogui.dragRel(-200,0)
pyautogui.sleep(1)
pyautogui.dragRel(0,-200)
pyautogui.sleep(1)
pyautogui.dragRel(100,-100)
pyautogui.sleep(1)
pyautogui.dragRel(100,100)
pyautogui.sleep(1)
pyautogui.dragRel(400,0)
pyautogui.sleep(1)
pyautogui.dragRel(-100,-100)
pyautogui.sleep(1)
pyautogui.dragRel(-400,0)
pyautogui.sleep(1)
pyautogui.click(1199,600)
pyautogui.sleep(1)
pyautogui.dragRel(0,200)
pyautogui.sleep(1)
pyautogui.dragRel(-400,0)
pyautogui.sleep(1)
pyautogui.click(739,799)
pyautogui.sleep(1)
pyautogui.dragRel(0,-100)
pyautogui.sleep(1)
pyautogui.dragRel(50,0)
pyautogui.sleep(1)
pyautogui.dragRel(0,100)
pyautogui.sleep(1)
pyautogui.click(492,83)
pyautogui.sleep(1)
pyautogui.click(1253,483)
pyautogui.sleep(1)
pyautogui.dragRel(100,-100)
pyautogui.sleep(1)
