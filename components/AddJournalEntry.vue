<script setup lang="ts">


const options = ['Arabica', 'Robusta', 'Blend', 'Grapes', 'Pineapple']
</script>

<template>
  <div class="add-journal-entry">
  <form>
    <Input type="text"  placeholder="Coffee Name" />
    <Input type="text"  placeholder="Origin" />
    <Input type="date"  placeholder="Date" />
    <Input type="text"  placeholder="Location" />
    <Select  placeholder="Price" />
    <Input type="text"  placeholder="Coffee Name" />
    <Select>
      <SelectTrigger>
        <SelectValue placeholder="Select a Bean Type" />
      </SelectTrigger>
      <SelectContent>
        <SelectGroup>
          <SelectLabel>Fruits</SelectLabel>
          <SelectItem value="apple">
            Apple
          </SelectItem>
        </SelectGroup>
      </SelectContent>
    </Select>
    <Select>
      <SelectTrigger>
        <SelectValue placeholder="Select a Roast" />
      </SelectTrigger>
      <SelectContent>
        <SelectGroup>
          <SelectLabel>Roast</SelectLabel>
          <SelectItem value="apple">
            Apple
          </SelectItem>
        </SelectGroup>
      </SelectContent>
    </Select>
    <Input />
    <Textarea placeholder="Additional Notes and Thoughts"/>
    <Button />
  </form>
  </div>
</template>

<style scoped>

</style>