from danger_python.danger import danger

# Verificar se o título do PR contém a tag 'Env'
pr_title = danger.github.pr_title

if "env" not in pr_title.lower():
    fail("🚨 O título do Pull Request deve incluir a tag 'Env'!")
