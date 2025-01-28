## Запуск Playbook
# Для сервера мониторинга
ansible-playbook -i inventories/production/ playbooks/monitoring.yml

# Для целевого сервера
ansible-playbook -i inventories/production/ playbooks/target.yml
