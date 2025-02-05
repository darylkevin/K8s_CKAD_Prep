# K8s Documentation

https://kubernetes.io/docs/home/

# Killer.sh Simulation

https://www.youtube.com/watch?v=LFMp-DgJtoo&list=PLpbwBK0ptssyIgAoHR-611wt3O9wobS8T

# CKAD Learning Materials

https://learn.kodekloud.com/user/courses/udemy-labs-certified-kubernetes-application-developer
https://gist.github.com/sagarhm/ae6968e620881ae04ab35584a80274a7

https://github.com/dgkanatsios/CKAD-exercises
https://github.com/ibrahimatay/CKAD-Exercises
https://github.com/saikrishnama/k8-administration/blob/master/exam/Practice%20Enough%20With%20These%20150%20Questions%20for%20the%20CKAD%20Exam.pdf
https://github.com/jamesbuckett/ckad-questions?tab=readme-ov-file

# TIPS

https://medium.com/@shamre/notes-for-passing-the-ckad-exam-and-understanding-the-concepts-of-kubernetes-8de04720279b
https://medium.com/@linoleparquet/ckad-tip-ensure-your-deployment-with-a-temporary-container-f21054aefcc7
https://kavinduchamiran.medium.com/my-two-cents-on-passing-ckad-in-2022-ffbb7f1c65be
https://mengying-li.medium.com/failed-ckad-first-attempt-my-journey-to-improve-exam-score-from-53-to-98-in-a-month-part-2-f9e56f47cdf9

# K8s PLAYGROUND

https://killercoda.com/playgrounds/scenario/ckad

# INFO Dump

1. Less intuitive areas

- Deprecated APIs and Features:
  Identify and suggest alternatives for deprecated Kubernetes APIs (e.g., from extensions/v1beta1 to apps/v1).
  Understand the impact of upgrading Kubernetes versions on deprecated APIs.
- Blue-Green Deployments and Canary Releases:
  Implement basic versioning and deployment strategies in Kubernetes using tools like Argo Rollouts.
- Pod communications without updating Network Policies:
  Understand how to restrict pod-to-pod communication without updating Network Policies.
- Limit Ranges
  A LimitRange is a policy to constrain the resource allocations (limits and requests) that you can specify for each applicable object kind (such as Pod or PersistentVolumeClaim) in a namespace.
- Docker commands:
  Tasks with docker shouldn't be that difficult, but make sure you know the basic commands like build, run, pull, push, save and load. You could also be asked to use Podman but don't worry: Docker and Podman have the same or nearly the same syntax.
