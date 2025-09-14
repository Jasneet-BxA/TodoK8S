load('ext://nerdctl', 'nerdctl_build')

nerdctl_build(
   ref='todo',
   context='./my-app',
   dockerfile='./my-app/Dockerfile'
)
k8s_yaml(helm('./charts/todo'))

k8s_resource('todo', port_forwards=3000)


