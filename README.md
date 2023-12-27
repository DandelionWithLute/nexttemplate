const Email = session.user.email
    const validEmail = Email.toLowerCase()


const post = await prisma.post.create({
      data: {
        slug: "fashion",
        title: "fashiontitle",
        desc: "fashiondesc",
        catSlug: "fashioncatSlug",
        userEmail: "john@gmail.com",
      },



try {
    const body = await req.json();
    const { title, desc, img, slug, catSlug } = body;
    const post = await prisma.post.create({
      data: { ...body, userEmail: session.user.email },
    });


import authLinks navbar footer 
context/ThemeContext.jsx themeToggle
featured categoryList card cardList
menuPosts menuCategories pagination


signIn("credentials", {
      email,
      password,
    });

  const fetcher = (...args) => fetch(...args).then((res) => res.json());

  const { data, mutate, error, isLoading } = useSWR(
    `/api/posts?username=${session?.data?.user.name}`,
    fetcher
  );

todo:
authjs authorize

http://localhost:3000/dashboard/login?error=Error:%20Illegal%20arguments:%20string,%20undefined


docker run --rm -p 5432:5432 -e POSTGRES_HOST_AUTH_METHOD=trust postgres
@\app\api\auth\[...nextauth]\route.js
const handler = NextAuth({})
try to find user
if(user)try catch (check password correct? return user : user not found!)

<input>: The Input (Form Input) element
https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input




This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
