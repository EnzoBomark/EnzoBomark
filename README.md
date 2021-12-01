### 👋 Welcome!

```TypeScript
// Current Skills
const languages = ['JavaScript', 'TypeScript', 'Php', 'C#', 'Bash'] as const;

const frontend = ['React', 'ReactNative', 'Gatsby', 'Next', 'Angular'] as const;

const backend = ['Express', 'Laravel'] as const;

const testing = ['Jest', 'Mocha'] as const;

const deploying = ['GitHub', 'Netlify', 'Heroku', 'Vercel', 'GatsbyCloud'] as const;

const design = ['PhotoShop', 'XD', 'Figma'] as const;

const other = ['AWS', 'GCS', 'WordPress'] as const;

interface IFavoriteSkills {
  languages: typeof languages[keyof typeof languages];
  frontend: typeof frontend[keyof typeof frontend];
  backend: typeof backend[keyof typeof backend];
  testing: typeof testing[keyof typeof testing];
  deploying: typeof deploying[keyof typeof deploying];
  design: typeof design[keyof typeof design];
  other: typeof other[keyof typeof other];
}

const EnzoBomark: IFavoriteSkills = {
  languages: 'TypeScript',
  frontend: 'Gatsby',
  backend: 'Express',
  testing: 'Jest',
  deploying: 'GatsbyCloud',
  design: 'PhotoShop',
  other: 'GCS',
};
```
