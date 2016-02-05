# Wekan

[Wekan](https://github.com/wekan/wekan)app for IndieHosters.

Wekan is an open-source and collaborative kanban board application.

Whether you’re maintaining a personal todo list, planning your holidays with some friends, or working in a team on your next revolutionary idea, Kanban boards are an unbeatable tool to keep your things organized. They give you a visual overview of the current state of your project, and make you productive by allowing you to focus on the few items that matter the most.

## How to run this

Run the install script with the right env variables.
And then:

```bash
docker-compose up
```

And all the data will be located under the `./data` folder.

## How to Backup this

Just run:

```bash
./BACKUP
```

This will create a dump of the mongo database. Then just copy the data folder to a safe location and you should be fine!

## Question?

If you have any questions, don't hesitate to open issues.
