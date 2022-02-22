<h2> Olá, eu sou o Diego!</h2><img src="https://komarev.com/ghpvc/?username=Carnage-ctrl&color=red" alt="Carnage-ctrl" /> 

```C
#include <gtk/gtk.h>
#include <stdio.h>
#include <stdlib.h>

GtkWidget* Window;
GtkWidget* Button;
GtkWidget* Dialog;

static void ExibirUmaVerdade();

int main(int argc, char *argv[])
{
    gtk_init(&argc, &argv);
    
    Window = gtk_window_new(GTK_WINDOW_TOPLEVEL);
    Button = gtk_button_new_with_label("Mostrar uma verdade");
    Dialog = gtk_message_dialog_new(
        NULL, GTK_DIALOG_MODAL, GTK_MESSAGE_INFO, GTK_BUTTONS_OK, "Nada é melhor do que C!"
    );
    
    gtk_widget_show_all(Window);
    gtk_widget_show_all(Button);
    gtk_container_add(GTK_CONTAINER(Window), Button);
    g_signal_connect(G_OBJECT(Button), "clicked", G_CALLBACK(ExibirUmaVerdade), NULL);
    
    gtk_main();
    
    return 0;
}

static void ExibirUmaVerdade()
{
    gtk_dialog_run(GTK_DIALOG(Dialog));
    gtk_widget_destroy(Dialog);
}

```

<p align="left">
  <a href="https://github.com/Carnage-ctrl" target="_blank">
    <img align="left" src="https://github-readme-stats.vercel.app/api?username=Carnage-ctrl&theme=react&show_icons=true">
  </a>
</p>

<h2>Linguagens que utilizo constantemente:</h2>
<code><img width="40" src="https://img.icons8.com/color/452/javascript--v1.png"></code>
<code><img width="40" src="https://img.icons8.com/color/452/typescript.png"></code>
<code><img width="40" src="https://iconarchive.com/download/i99610/blackvariant/button-ui-requests-6/iTerm.ico"></code>
<code><img width="40" src="https://img.icons8.com/color/344/c-programming.png"></code>
<code><img width="40" src="https://cdn3.iconfinder.com/data/icons/logos-and-brands-adobe/512/267_Python-512.png"></code>

