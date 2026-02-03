---

# **SECTION THREE — THE HOW**

> “Once I committed to building the system myself,
> the question became *how* to build it
> in a way that a volunteer‑run nonprofit could actually sustain.”

---

## **1. Use the stack that made sense for both work and the project**

> “My backend skills were current, but my frontend was out of date.  
> So I aligned the project with the direction my day job was already moving.
>
> GraphQL was supposed to be the future, and I needed to learn it anyway.  
> Amplify gave me a simple way to manage backend infrastructure
> without becoming a full‑time cloud engineer.
>
> The stack wasn’t about novelty or purity —
> it was about choosing tools that made sense for my time, my job,
> and the long‑term sustainability of the platform.”

---

## **2. Naming should work the same way a UI works**

> “A UI is like a joke — if I have to explain it, it isn’t very good.
>
> Naming is the same.  
> If the name doesn’t reveal the intent, the abstraction is wrong.
>
> A good name makes the code self‑explanatory.  
> A bad name forces the reader to reverse‑engineer the author’s thinking.”

---

## **3. No hidden magic**

> “No implicit side effects.  
> No invisible state.  
> No surprise behavior.  
> Everything the system does is explicit and readable.”

---

## **4. Risk‑based documentation**

> “I documented code, decisions, and abstractions as I made them
> so I wouldn’t have to remember them later.
>
> If something was likely to be forgotten,
> or likely to cause confusion or breakage in the future, I wrote it down.  
> If the code could explain itself, I let it.
>
> The goal wasn’t to document everything —
> just the things that would hurt if they were forgotten.”

---

## **5. Design for maintainers I haven’t met**

> “I built the system assuming someone else will maintain it one day.  
> Maybe a volunteer.  
> Maybe a student.  
> Maybe someone from the community.
>
> So the code had to be readable, the architecture obvious, and the decisions documented.”

---

## **6. KISS: Build for today, plan for tomorrow**

> “Build for today, plan for tomorrow, but don’t over‑engineer.  
> Tomorrow’s problems belong to tomorrow.
>
> Every abstraction had to earn its place.  
> If the problem wasn’t real yet, I didn’t solve it early.”

---

## **7. Operational simplicity because it’s volunteer‑run**

> “The system had to be cheap to run, easy to deploy, and simple to monitor —
> because this is a volunteer‑run platform.
>
> I built and monitored it in the evenings and on weekends.  
> It cannot be a full‑time job.  
> It cannot afford to be.
>
> Operational simplicity wasn’t a preference.  
> It was a requirement.”

---

## **8. Go slow to go fast (clarity over developer convenience)**

> “I optimized for clarity.
>
> New features and new domains take longer to build,
> but bugs and issues reveal themselves faster and are repaired faster.
>
> It’s operational convenience over initial developer convenience.  
> Going slow at the beginning is what makes the system fast everywhere else.”

---