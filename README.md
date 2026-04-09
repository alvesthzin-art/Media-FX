
🎓 **Média Final — Projeto em JavaFX**
Um aplicativo desenvolvido em **JavaFX** para calcular a **média final de um aluno**, exibindo automaticamente sua **situação escolar** (Aprovado, Recuperação ou Reprovado).



---




🖥️ **Tecnologias**

* Java 17+
* JavaFX SDK
* IDE recomendada: IntelliJ IDEA ou Eclipse com suporte a JavaFX



---




💡 **Funcionalidades**

* Inserção do **nome do aluno** e **4 notas**
* Cálculo automático da **média final**
* Exibição da **situação do aluno**

  * ✅ Aprovado — média ≥ 6
  * ⚠️ Recuperação — média entre 4 e 5.9
  * ❌ Reprovado — média < 4
* Botões interativos:

  * **Calcular Média** — processa e mostra o resultado
  * **Limpar** — apaga todos os campos
  * **Sair** — exibe uma confirmação antes de fechar



---




🚀 **Como Executar**

1. Certifique-se de ter o **JavaFX** configurado no ambiente.
2. Compile e execute o projeto:

   ```bash
   javac --module-path "path/javafx/lib" --add-modules javafx.controls br/senai/sp/jandira/media_final/Media_Final.java
   java --module-path "path/javafx/lib" --add-modules javafx.controls br.senai.sp.jandira.media_final.Media_Final
   ```

   

---




📚 **Conceitos Aplicados**

* Estruturas de repetição (`while`)
* Estruturas condicionais (`if / else if / else`)
* Manipulação de eventos (`setOnAction`)
* Uso de **BorderPane** e **VBox** para layout
* Exibição de mensagens com **Alert**



---




🧩 **Layout (Interface)**
O design foi construído com **BorderPane**, organizando a tela em regiões:

* 🧾 Topo — título da escola
* 🧍‍♂️ Esquerda — formulário com nome e notas
* 🧮 Direita — botões de ação
* 📊 Inferior — exibição dos resultados


👨‍💻 Desenvolvedor
<table style="border: none;">
<tr>
<td align="center">
<a href="#">
<img src="https://github.com/alvesthzin-art.png" width="100px;" alt="Avatar"/><br />
<sub><b>@alvesthzin-art</b></sub>
</a>
</td>
</tr>
</table>




