from danger_python.danger import danger

# Verificar se o PR tem a tag 'Env'
pr_title = danger.github.pr_title

if "Env" not in pr_title:
    message = (
        "🚨 O título do Pull Request deve incluir a tag 'Env' para identificar o ambiente!"
    )
    fail(message)
