# TypeScript Starter Project

This is a starter project to either serve as a template for new projects or a place to pull configs/setup from for other projects.

Includes:

- ✅ TypeScript
- ❌ ESLint
- ❌ Prettier
- ❌ Unit Tests

## Notes

- You probably don't need the `rimraf`/`pnpm run clean` step if you're making a frontend project or using some sort of bundler (vite, etc). For backend/CLI projects, you do need to clean up between builds or there will be leftover artifacts of old files in your dist and who wants that?
