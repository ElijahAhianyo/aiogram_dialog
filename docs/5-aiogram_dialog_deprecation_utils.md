# Aiogram Dialog Deprecation Utils

[_Documentation generated by Documatic_](https://www.documatic.com)

<!---Documatic-section-Codebase Structure-start--->
## Codebase Structure

<!---Documatic-block-system_architecture-start--->
```mermaid
None
```
<!---Documatic-block-system_architecture-end--->

# #
<!---Documatic-section-Codebase Structure-end--->

<!---Documatic-section-aiogram_dialog.deprecation_utils.manager_deprecated-start--->
## aiogram_dialog.deprecation_utils.manager_deprecated

<!---Documatic-section-manager_deprecated-start--->
<!---Documatic-block-aiogram_dialog.deprecation_utils.manager_deprecated-start--->
<details>
	<summary><code>aiogram_dialog.deprecation_utils.manager_deprecated</code> code snippet</summary>

```python
def manager_deprecated(manager: Optional[Any]):
    if manager is not None:
        warnings.warn('Passing `DialogManager` instance directly is deprecated and will be removed in aiogram_dialog==2.0', DeprecationWarning, stacklevel=3)
```
</details>
<!---Documatic-block-aiogram_dialog.deprecation_utils.manager_deprecated-end--->
<!---Documatic-section-manager_deprecated-end--->

# #
<!---Documatic-section-aiogram_dialog.deprecation_utils.manager_deprecated-end--->

[_Documentation generated by Documatic_](https://www.documatic.com)