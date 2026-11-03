if (texto === "") {
    alert("Digite uma tarefa!");
    return;
}

const tarefa = document.createElement("li");
tarefa.textContent = texto;

tarefa.addEventListener("click", function() {
    tarefa.style.textDecoration = "line-through";
    tarefa.style.opacity = "0.5";
});

const botaoExcluir = document.createElement("button");
botaoExcluir.textContent = "Excluir";

botaoExcluir.addEventListener("click", function(event) {
    event.stopPropagation();
    tarefa.remove();
});

tarefa.appendChild(botaoExcluir);
listaTarefas.appendChild(tarefa);

campoTarefa.value = "";
