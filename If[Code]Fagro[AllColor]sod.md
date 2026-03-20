# 💀 IF[CODE]FAGRO[ALLCOLOR]SOD 💀

## Что это такое?
Это система обработки критических ошибок для ФАГРО ОС с поддержкой экранов смерти разных цветов.

## 📋 СОДЕРЖАНИЕ

### 1. Коды ошибок ФАГРО ОС

| Код | Название | Описание |
|-----------|-------------------|------------------------------------------|
| `F4GR001` | KERNEL_PANIC | Общая ошибка ядра |
| `F4GR002` | GIST_CONNECTION_FAILED | Не удалось подключиться к Gist |
| `F4GR003` | APP_SANDBOX_VIOLATION | Нарушение песочницы приложения |
| `F4GR004` | CRYPTO_MODULE_FAILURE | Ошибка модуля шифрования |
| `F4GR005` | BOOT_CONFIG_CORRUPTED | Конфигурация загрузки повреждена |
| `F4GR006` | REPOSITORY_CHAIN_BROKEN | Цепочка репозиториев нарушена |
| `F4GR007` | DEPENDENCY_CYCLE_DEFECTED | Обнаружен циклическая зависимость |
| `F4GR008` | VIRTUAL_MEMORY_EXHAUSTED | Виртуальная память исчерпана |
| `F4GR009` | PROCESS_TERMINATION_FAILED | Не удалось завершить процесс |
| `F4GR00A` | SYSTEM_FILE_CORRUPTED | Системный файл поврежден |
| `F4GR00B` | USER_PERMISSION_DENIED | Недостаточно прав |
| `F4GR00C` | HACKER_MODE_CONFLICT | Конфликт хакер-режима |
| `F4GR00D` | SANDBOX_ESCAPE_ATTEMPT | Попытка побега из песочницы |
| `F4GR00E` | STACK_OVERFLOW_DETECTED | Переполнение стека |
| `F4GR00F` | HEAP_CORRUPTION | Повреждение кучи |
| `F4GR010` | FILESYSTEM_CORRUPTED | Файловая система повреждена |
| `F4GR011` | DISK_READ_ERROR | Ошибка чтения диска |
| `F4GR012` | DISK_WRITE_ERROR | Ошибка записи на диск |
| `F4GR013` | MOUNT_FAILED | Не удалось смонтировать раздел |
| `F4GR014` | UNMOUNT_FAILED | Не удалось размонтировать |
| `F4GR015` | DISK_FULL | Диск переполнен |
| `F4GR016` | FILE_NOT_FOUND | Системный файл не найден |
| `F4GR017` | ACCESS_DENIED | Отказано в доступе |
| `F4GR018` | INODE_CORRUPTED | Повреждение inode |
| `F4GR019` | JOURNAL_ERROR | Ошибка журналирования |
| `F4GR020` | FILESYSTEM_RO | Файловая система только для чтения |
| `F4GR021` | TEST_MODE_ACTIVE | Активен тестовый режим |
| `F4GR022` | TEST_CRASH_SIMULATED | Симулированное падение |
| `F4GR023` | BENCHMARK_ERROR | Ошибка бенчмарка |
| `F4GR024` | STRESS_TEST_FAILED | Стресс-тест не пройден |
| `F4GR025` | MEMORY_TEST_ERROR | Ошибка теста памяти |
| `F4GR026` | CPU_TEST_ERROR | Ошибка теста процессора |
| `F4GR027` | DISK_TEST_ERROR | Ошибка теста диска |
| `F4GR028` | NETWORK_TEST_ERROR | Ошибка теста сети |
| `F4GR029` | GPU_TEST_ERROR | Ошибка теста графики |
| `F4GR030` | AUDIO_TEST_ERROR | Ошибка теста аудио |

### 2. Цвета экрана смерти

| Цвет | Код | Вид |
|------|-----|-----|
| 🔵 Синий | `blue` | Классический Windows |
| 🔴 Красный | `red` | Опасная ошибка |
| 🟢 Зеленый | `green` | Матрица |
| 🟡 Желтый | `yellow` | Предупреждение |
| 🟣 Фиолетовый | `purple` | Гламурный |
| 🔵 Голубой | `cyan` | Морской |
| ⚪ Белый | `white` | Инверсия |
| ⚫ Черный | `black` | Хакерский |

### 3. Примеры использования

'''python
# Простой вызов
handle_critical_error("F4GR001", "Ошибка ядра", "blue")

# С подробным описанием
handle_critical_error(
    error_code="F4GR777",
    reason="Не удалось загрузить системный модуль",
    details="Файл kernel.sys поврежден или отсутствует",
    color="red"
)

# Ошибка файловой системы
handle_critical_error(
    error_code="F4GR010",
    reason="Критическое повреждение файловой системы",
    details="Superblock поврежден, требуется fsck",
    color="yellow"
)

# Тестовая ошибка
handle_critical_error(
    error_code="F4GR021",
    reason="Тестовый режим активирован",
    details="Это не настоящая ошибка, просто тест",
    color="green"
)'''


# 💀 IF[CODE]FAGRO[ALLCOLOR]SOD 💀

## What is it?
This is a critical error handling system for PHAGRO OS with support for death screens in different colors.

## 📋 CONTENT

###1. PHAGRO OS Error Codes

| Code | Name | Description |
|-----------|-------------------|------------------------------------------|
| `F4GR001` | KERNEL_PANIC | Common Core error |
| `F4GR002` | GIST_CONNECTION_FAILED | Couldn't connect to Gist |
| `F4GR003` | APP_SANDBOX_VIOLATION | Violation of the application sandbox |
| `F4GR004` | CRYPTO_MODULE_FAILURE | Encryption module error |
| `F4GR005` | BOOT_CONFIG_CORRUPTED | Boot configuration is corrupted |
| `F4GR006` | REPOSITORY_CHAIN_BROKEN | The repository chain is broken |
| `F4GR007` | DEPENDENCY_CYCLE_DEFECTED | Cyclical dependence has been discovered |
| `F4GR008` | VIRTUAL_MEMORY_EXHAUSTED | Virtual memory is exhausted |
| `F4GR009` | PROCESS_TERMINATION_FAILED | Couldn't complete the process |
| `F4GR00A` | SYSTEM_FILE_CORRUPTED | The system file is corrupted |
| `F4GR00B` | USER_PERMISSION_DENIED | Not enough rights |
| `F4GR00C` | HACKER_MODE_CONFLICT | Hacker mode conflict |
| `F4GR00D` | SANDBOX_ESCAPE_ATTEMPT | An attempt to escape from the sandbox |
| `F4GR00E` | STACK_OVERFLOW_DETECTED | Stack Overflow |
| `F4GR00F` | HEAP_CORRUPTION | Heap Damage |
| `F4GR010` | FILESYSTEM_CORRUPTED | File system is corrupted |
| `F4GR011` | DISK_READ_ERROR | Disk reading error |
| `F4GR012` | DISK_WRITE_ERROR | Error writing to disk |
| `F4GR013` | MOUNT_FAILED | Couldn't mount the partition |
| `F4GR014` | UNMOUNT_FAILED | Couldn't unmount |
| `F4GR015` | DISK_FULL | Disk is full |
| `F4GR016` | FILE_NOT_FOUND | System file not found |
| `F4GR017` | ACCESS_DENIED | Access denied |
| `F4GR018` | INODE_CORRUPTED | Inode corruption |
| `F4GR019` | JOURNAL_ERROR | Logging error |
| `F4GR020` | FILESYSTEM_RO | Read-only file system |
| `F4GR021` | TEST_MODE_ACTIVE | Test mode is active |
| `F4GR022` | TEST_CRASH_SIMULATED | Simulated crash |
| `F4GR023` | BENCHMARK_ERROR | Benchmark error |
| `F4GR024` | STRESS_TEST_FAILED | Stress test failed |
| `F4GR025` | MEMORY_TEST_ERROR | Memory Test error |
| `F4GR026` | CPU_TEST_ERROR | Processor Test error |
| `F4GR027` | DISK_TEST_ERROR | Disk Test error |
| `F4GR028` | NETWORK_TEST_ERROR | Network Test Error |
| `F4GR029` | GPU_TEST_ERROR | Graphics Test error |
| `F4GR030` | AUDIO_TEST_ERROR | Audio Test Error |

### 2. Colors of the death screen

| Color | Code | Type |
|------|-----|-----|
| 🔵 Blue | `blue` | Classic Windows |
| 🔴 Red | `red` | A dangerous mistake |
| 🟢 Green | `green` | The Matrix |
| 🟡 Yellow | `yellow` | Warning |
| 🟣 Purple | `purple` | Glamorous |
| 🔵 Blue | `cyan` | Marine |
| ⚪ White | `white` | Inversion |
| ⚫ Black | `black` | Hacker |

### 3. Usage examples

'''python
# Simple challenge
handle_critical_error("F4GR001", "Kernel error", "blue")

# With a detailed description
handle_critical_error(
    error_code="F4GR777",
    reason="Failed to load the system module",
    details="File kernel.sys damaged or missing",
    color="red"
)

# File system error
handle_critical_error(
    error_code="F4GR010",
    reason="Critical file system corruption",
    details="Superblock is damaged, requires fsck",
color="yellow"
)

# Test error
handle_critical_error(
    error_code="F4GR021",
    reason="Test mode is activated",
    details="It's not a real bug, just a test.",
    color="green"
)'''
