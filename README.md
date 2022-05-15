### Hi, my name is Atsukoro 👋

```typescript
async function introduction() : Promise<void> {
    const yourName = await prompt("Please enter your name");

    const learning : String[] = [ "Rust", "C++" ];
    const doing : String[] = [ "Typescript", "Javascript" ];

    process.stdout.write(`
    Hi ${yourName}, I am Atsukoro 👋, a 17 years web developer mainly focusing on backend but I do frontend pretty well too.
    If you want to discuss something with me, you can contact me on my Discord (Atsukoro#6323)

    💻 Languages I am learning now are ${learning.join(", ")} and currently using ${doing.join(", ")}!
    If you want to lookup my full stack, you can find it here at this link https://stackshare.io/atsukoro1/my-stack
    `);
}
```
