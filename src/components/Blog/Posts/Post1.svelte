<script>
  import { link } from "svelte-routing";
  export let short;
</script>

<div class="container d-flex flex-column align-items-center">
  {#if short}
    <h1>How to Lie Down</h1>
    <img src="/images/kangaroo.jpeg" class="w-50 m-5 shadow" alt="" />
    <p class="my-5">
      I practice active rest just about every day, and have been doing so for
      about 10 years. I welcome you to try it.
    </p>
    <a href="/blog/1" class="btn mb-5" use:link>More</a>
  {:else}
    <h1>How to Lie Down</h1>
    <img src="/images/kangaroo.jpeg" class="w-50 m-5 shadow" alt="" />
    <p>
      I practice active rest just about every day, and have been doing so for
      about 10 years. I welcome you to try it.
    </p>
    <p>The basics:</p>
    <p>
      Find a quiet area where you won’t be disturbed. If the surface is not soft
      or carpeted, place a yoga mat or towel on the ground. Place a stack of
      books on the ground that support your neck.
    </p>
    <p>
      Tips for determining the height of books - if you stand with your back
      against a wall, chances are, unless you really strain your neck, the back
      of your head will not touch the wall. <strong
        >This is the straining you’re trying to prevent with the books.</strong
      > Books can be substituted with anything with a similar gentle firmness - a
      pillow or cushion, however, likely won’t provide the correct structure and
      thus may do more harm than good.
    </p>
    <p>
      Essentially, you’re looking for the amount of books that allow the front
      of your neck to stay free while the back of your neck also stays free.
    </p>
    <p>
      The opportunity this position provides, after all, is to that in which one
      might experience of not “using” the neck as actively as we might be used
      to in daily life - often a little too much. You may be thinking - no way,
      I know how to use my neck! Well, great! But just know that the benefits
      from improvement in this instance might be quite favorable.
    </p>
    <p>Think about it - that “pain in the neck”, or a neck-ache or whatever.</p>
    <p>
      Giving yourself a chance to release the neck is to practice a skill you
      may find coming in handy in many instances.
    </p>
    <p>
      Once you have the correct number of books, place them in a pile on one of
      the ends of the mat. This is where you will rest your head.
    </p>
    <p>
      This position aims to help us release out of the habit of pulling our
      heads back and down. But don’t really worry about exactly what that means.
      It’s meant to allow us to release our neck, and possibly more.
    </p>
    <p>So just start there, and if you’d like, try some of these thoughts.</p>

    <ul>
      <li>I never have to move again</li>
      <li>I am what I am, and that’s fine</li>
      <li>My neck has to do nothing</li>
      <li>I am melting into the floor</li>
    </ul>
    <p>
      Practicing this lie down, and learning AT, can help in ways that you may
      not have expected. And it can all just start with this simple practice.
    </p>
    <a href="/blog" class="btn" use:link>Back to blogs</a>
  {/if}
</div>
