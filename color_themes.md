# Dr. Abida Nadaf Website — Color Theme Presets

Here are the color theme configurations for testing. You can copy-paste any theme's `tailwind.config` block and `<style>` rules into `<head>` of `dr_abida_nadaf_coaching (7).html` and `index.html`.

---

## 1. Greenish Blue (Mineral Ocean Teal & Seafoam Mist)

```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                sanctuary: { 50: '#F7FAF9', 100: '#F0F6F5', 200: '#E2ECEB', 300: '#CFE0DE', 400: '#B6CBC9', 500: '#94ADA9' },
                peachmist: { 50: '#F4FAF9', 100: '#E4F4F2', 200: '#CEECE8', 300: '#B0DFD9', 400: '#7DC8BF', 500: '#48ABA0' },
                roseblush: { 50: '#F3FAF9', 100: '#E3F2F1', 200: '#CBE5E4', 300: '#A9D1CF' },
                terracotta: { DEFAULT: '#1B6B78', hover: '#13545E', soft: '#E9F5F5', glow: 'rgba(27, 107, 120, 0.15)' },
                charcoal: { 900: '#0F1E22', 800: '#182C32', 700: '#2A434B', 600: '#435E67', 500: '#67848E', 400: '#95AFB8' },
                sage: { light: '#E8F5F3', DEFAULT: '#338882', dark: '#1F5D59' }
            },
            fontFamily: {
                serif: ['"Fraunces"', 'Georgia', 'serif'],
                sans: ['"Plus Jakarta Sans"', '-apple-system', 'sans-serif'],
            },
            boxShadow: {
                'subtle': '0 4px 20px -2px rgba(15, 30, 34, 0.04)',
                'card': '0 12px 32px -4px rgba(15, 30, 34, 0.06), 0 4px 12px -2px rgba(15, 30, 34, 0.03)',
                'floating': '0 20px 48px -8px rgba(27, 107, 120, 0.12), 0 8px 20px -4px rgba(15, 30, 34, 0.04)',
                'hover-card': '0 22px 45px -8px rgba(15, 30, 34, 0.09), 0 8px 16px -4px rgba(27, 107, 120, 0.1)'
            }
        }
    }
}
```

```css
body {
    background-color: #F0F6F5;
    color: #0F1E22;
    selection-background-color: #CEECE8;
}

::-webkit-scrollbar-track {
    background: #F0F6F5;
}

::-webkit-scrollbar-thumb {
    background: #CFE0DE;
    border-radius: 999px;
}

::-webkit-scrollbar-thumb:hover {
    background: #1B6B78;
}
```

---

## 2. Light Purple & Pink (Lavender Mist & Orchid Blush)

```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                sanctuary: { 50: '#FAF7FA', 100: '#F6F1F6', 200: '#EDE4EE', 300: '#E0D2E2', 400: '#C9B6CE', 500: '#A892AF' },
                peachmist: { 50: '#FDF7FA', 100: '#FAEEF4', 200: '#F5DCE8', 300: '#EDBDD4', 400: '#DF91B8', 500: '#CA5E94' },
                roseblush: { 50: '#FDF7F9', 100: '#FCEEF3', 200: '#F8DCE6', 300: '#EDAEC4' },
                terracotta: { DEFAULT: '#8A3B6E', hover: '#712D57', soft: '#FDF4F8', glow: 'rgba(138, 59, 110, 0.14)' },
                charcoal: { 900: '#20121C', 800: '#2E1B29', 700: '#462F3E', 600: '#614658', 500: '#86687C', 400: '#AC91A3' },
                sage: { light: '#F7EDF5', DEFAULT: '#7A4D74', dark: '#562E51' }
            },
            fontFamily: {
                serif: ['"Fraunces"', 'Georgia', 'serif'],
                sans: ['"Plus Jakarta Sans"', '-apple-system', 'sans-serif'],
            },
            boxShadow: {
                'subtle': '0 4px 20px -2px rgba(32, 18, 28, 0.04)',
                'card': '0 12px 32px -4px rgba(32, 18, 28, 0.06), 0 4px 12px -2px rgba(32, 18, 28, 0.03)',
                'floating': '0 20px 48px -8px rgba(138, 59, 110, 0.12), 0 8px 20px -4px rgba(32, 18, 28, 0.04)',
                'hover-card': '0 22px 45px -8px rgba(32, 18, 28, 0.09), 0 8px 16px -4px rgba(138, 59, 110, 0.1)'
            }
        }
    }
}
```

```css
body {
    background-color: #F6F1F6;
    color: #20121C;
    selection-background-color: #F5DCE8;
}

::-webkit-scrollbar-track {
    background: #F6F1F6;
}

::-webkit-scrollbar-thumb {
    background: #E0D2E2;
    border-radius: 999px;
}

::-webkit-scrollbar-thumb:hover {
    background: #8A3B6E;
}
```

---

## 3. Orange & Lemon Yellow (Sunlit Citrus & Warm Honey Amber)

```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                sanctuary: { 50: '#FFFEFA', 100: '#FFFDF5', 200: '#FDF7E4', 300: '#F5ECCD', 400: '#E4D5AA', 500: '#C7B47E' },
                peachmist: { 50: '#FFFDF2', 100: '#FFFBE0', 200: '#FFF5B8', 300: '#FFE985', 400: '#FFD747', 500: '#F5B814' },
                roseblush: { 50: '#FFF9F4', 100: '#FFF0E4', 200: '#FFE0CA', 300: '#FFC299' },
                terracotta: { DEFAULT: '#C45A1C', hover: '#A8470E', soft: '#FFF6EE', glow: 'rgba(196, 90, 28, 0.15)' },
                charcoal: { 900: '#1E1810', 800: '#2E2419', 700: '#483928', 600: '#64513D', 500: '#8C745C', 400: '#B29B82' },
                sage: { light: '#F6F9EE', DEFAULT: '#728C38', dark: '#4E6221' }
            },
            fontFamily: {
                serif: ['"Fraunces"', 'Georgia', 'serif'],
                sans: ['"Plus Jakarta Sans"', '-apple-system', 'sans-serif'],
            },
            boxShadow: {
                'subtle': '0 4px 20px -2px rgba(30, 24, 16, 0.04)',
                'card': '0 12px 32px -4px rgba(30, 24, 16, 0.06), 0 4px 12px -2px rgba(30, 24, 16, 0.03)',
                'floating': '0 20px 48px -8px rgba(196, 90, 28, 0.12), 0 8px 20px -4px rgba(30, 24, 16, 0.04)',
                'hover-card': '0 22px 45px -8px rgba(30, 24, 16, 0.09), 0 8px 16px -4px rgba(196, 90, 28, 0.1)'
            }
        }
    }
}
```

```css
body {
    background-color: #FFFDF5;
    color: #1E1810;
    selection-background-color: #FFF5B8;
}

::-webkit-scrollbar-track {
    background: #FFFDF5;
}

::-webkit-scrollbar-thumb {
    background: #F5ECCD;
    border-radius: 999px;
}

::-webkit-scrollbar-thumb:hover {
    background: #C45A1C;
}
```

---

## 4. Warm Sanctuary & Terracotta (Original Luxury Earth Tone)

```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                sanctuary: { 50: '#FCFAF7', 100: '#FAF7F2', 200: '#F5ECE3', 300: '#EBDCCE', 400: '#DEC6B3', 500: '#C9A992' },
                peachmist: { 50: '#FFF9F5', 100: '#FFF1E8', 200: '#FDE2D2', 300: '#F9C9B0', 400: '#F4A682', 500: '#E87D52' },
                roseblush: { 50: '#FDF7F7', 100: '#F9ECEE', 200: '#F3D7DC', 300: '#E7B4BE' },
                terracotta: { DEFAULT: '#BA5333', hover: '#9E3F22', soft: '#FAF1EC', glow: 'rgba(186, 83, 51, 0.12)' },
                charcoal: { 900: '#1C1614', 800: '#2D2320', 700: '#483B37', 600: '#64544F', 500: '#8A7670', 400: '#B09F9A' },
                sage: { light: '#EEF3EE', DEFAULT: '#627A62', dark: '#455945' }
            },
            fontFamily: {
                serif: ['"Fraunces"', 'Georgia', 'serif'],
                sans: ['"Plus Jakarta Sans"', '-apple-system', 'sans-serif'],
            },
            boxShadow: {
                'subtle': '0 4px 20px -2px rgba(28, 22, 20, 0.04)',
                'card': '0 12px 32px -4px rgba(28, 22, 20, 0.06), 0 4px 12px -2px rgba(28, 22, 20, 0.03)',
                'floating': '0 20px 48px -8px rgba(186, 83, 51, 0.1), 0 8px 20px -4px rgba(28, 22, 20, 0.04)',
                'hover-card': '0 22px 45px -8px rgba(28, 22, 20, 0.09), 0 8px 16px -4px rgba(186, 83, 51, 0.08)'
            }
        }
    }
}
```

```css
body {
    background-color: #FAF7F2;
    color: #1C1614;
    selection-background-color: #FDE2D2;
}

::-webkit-scrollbar-track {
    background: #FAF7F2;
}

::-webkit-scrollbar-thumb {
    background: #EBDCCE;
    border-radius: 999px;
}

::-webkit-scrollbar-thumb:hover {
    background: #BA5333;
}
```
