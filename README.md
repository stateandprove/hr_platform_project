# HR Platform

## Задание

Вы разрабатываете HR-платформу для управления резюме. Вам дан готовый набор моделей, сериализаторов и представлений. Ваша задача — реализовать авторизацию, роли и разграничение доступа к операциям над резюме. На платформе предусмотрены следующие роли:

- `Кандидат`: может создавать, редактировать и просматривать только свои резюме;
- `HR-менеджер`: может просматривать резюме всех кандидатов, но не редактировать их.;
- `Администратор`: имеет полный доступ ко всем действиям (CRUD).

Настройте права доступа к API: кто может видеть, создавать, обновлять и удалять резюме — в зависимости от роли.

Проверьте работу через `/api/resumes/` после настройки модели пользователя и авторизации.
