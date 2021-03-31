https://arsen-tadtaev.github.io/rsschool-cv/cv

## Arseniy Tadtaev

### Contacts
- __Email__: arsen.tadtaev@gmail.com

### Summary
I love sports and football. Novice programmer. I want to improve my skills in web development.

### Skills
 JS, HTML, CSS.

### Code example
```typescript
/**
 * Преобразовывает число в формат с плавающей точкой для отображения финансовых показателей.
 * @param {number} number Число
 * @param {number} digits Количество цифр, которые надо отобразить после запятой
 */
export const financial = (
	number: number,
	digits: number = 3
): string | null => {
	if (!Number.isFinite(number)) return null;
	return new Intl.NumberFormat('ru-RU', {
		minimumFractionDigits: digits,
	}).format(number);
};
```

### Education
The Rolling Scopes School

### English
B2 probably