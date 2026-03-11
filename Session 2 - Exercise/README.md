# Session 2: Exercise

## Question

Make sure you have your Linux VM setup and running.

Register on Linux Journey website and read the following parts:

1. Command Line
2. Text-fu
3. User Management
4. Permissions

Download the `exercise_two.tar` file provided by your trainer from [here](https://drive.google.com/drive/u/0/folders/12TyoWnZI9740EQmDwqsOJju3MMer4af1).

Setup the challenge by running the following commands in your terminal:

```bash
sudo docker load --input exercise_two.tar
sudo docker run -p 2222:22 exercise_two:latest
```

Now you can easily connect to the challenge environment with:

```bash
ssh masar@localhost -p 2222
# Password is masar123
```

Your goal is to achieve the following:

1. Find the secret hidden file that has the secret ingredient (Hint: the file’s extension is `.txt`)
2. Explore your user permission and capabilities and leverage it in order to read the secret file.
3. Run `validate` command and provide it with the secret ingredient to get the flag.

**Deliverable:** You’re goal is to provide a brief PDF report that demonstrates the steps/commands you followed and executed that helped you to retrieve the flag.