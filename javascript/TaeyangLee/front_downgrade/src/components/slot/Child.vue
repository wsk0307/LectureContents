<template>
    <div>
        <p>Child 컴포넌트</p>
        <!--부모 컴포넌트의 일부를 자녀 컴포넌트에서 사용할 수 있게 해줌-->
        <slot></slot>
        <slot></slot>
        <slot></slot>
        <slot></slot>
        <slot></slot>
        <slot></slot>
        <slot></slot>
        <slot></slot>
    </div>
</template>



<style scoped>
p {
    border: 3px solid teal;
    padding: 4px;
}
</style>
