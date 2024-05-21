<script lang="ts">
	import Navigation from '$lib/components/header/Navigation.svelte';
	import Footer from '$lib/components/footer/Footer.svelte';
</script>

<div class="wrapper flex flex-col min-h-screen">
	<header>
		<div class="container m-auto mb-5">
			<div
				class="bg-article-img mx-3 mt-3 px-3 py-3 bg-no-repeat rounded-xl min-h-[120px] bg-[length:100%_100%] lg:min-h-[180px] xl:min-h-[200px] 2xl:min-h-[300px] 2xl:py-5"
			>
				<Navigation />
			</div>
		</div>
	</header>
	<main class="flex-auto">
		<slot />

		
		<section class="image mb-5">
			<div class="container m-auto">
				<picture class=" w-full">
					<source
						srcset="/img/all-article-web-page-content-img/article-anestesiologist.avif"
						type="image/avif"
					/>
					<source
						srcset="/img/all-article-web-page-content-img/article-anestesiologist.webp"
						type="image/webp"
					/>
					<img
						src="/img/all-article-web-page-content-img/article-anestesiologist.jpg"
						alt="article-anestesiologist"
					/>
				</picture>
			</div>
		</section>
		<section>
			<div class="container max-w-3xl m-auto">
				<div class="primary-requirements">
					<p class="mb-5">
						Кваліфікований анестезіолог має вміти працювати з усіма видами анестезії - загальною
						(так званим наркозом), регіонарною та місцевою.
					</p>
					<p class="mb-5">
						Вільні вакансії лікаря-анестезіолога в Польщі є у відділеннях інтенсивної терапії в
						державних і приватних закладах стаціонарного типу, а також в амбулаторіях, обладнаних
						власними малими операційними.
					</p>
					<h6 class="font-bold text-3xl mb-5">
						Кого візьмуть
						<span class=" text-biruza"> на роботу анестезіологом у польську клініку? </span>
					</h6>
					<p class="mb-5">
						На співбесіді з претендентом на посаду анестезіолога-реаніматолога роботодавець звертає
						увагу на наявність:
					</p>
					<ul class="flex flex-col gap-2 list-disc pl-5 mb-5">
						<li>диплома про закінчення вищого медичного навчального закладу у себе в країні;</li>
						<li>сертифіката післядипломної підготовки з анестезіології;</li>
						<li>досвіду роботи не менше 3 років протягом останніх 5 років;</li>
						<li>дозволу на здійснення лікарської діяльності від МОЗ;</li>
						<li>ліцензії від місцевих органів виконавчої влади;</li>
						<li>володіння польською мовою з орієнтацією на медичну специфіку.</li>
					</ul>
					<p class="mb-5">
						За інших рівних умов перевагу віддають претендентам, у резюме яких зазначено наявність
						важливих професійних та особистих якостей - стресостійкості, самовладання, зібраності,
						холоднокровності, хорошої пам'яті, а також неконфліктності, сумлінності та здатності
						ефективно працювати в команді.
					</p>
					<h6 class="text-3xl font-bold mb-5">
						Умови, що
						<span class="text-biruza"> надаються </span>
					</h6>
					<p class="mb-5">
						Влаштовуючись на роботу анестезіологом до Польщі, іноземний фахівець може гарантовано
						розраховувати на:
					</p>
					<ul class="list-disc pl-5 mb-5">
						<li>зарплату від 7500 злотих брутто на місяць з подальшим збільшенням;</li>
						<li>
							нормований робочий день і доплати за будь-які перепрацювання, зокрема, за добові
							чергування;
						</li>
						<li>європейські соціальні гарантії;</li>
						<li>
							забезпечення уніформою, інструментами, медичними препаратами, витратними матеріалами,
							професійною літературою;
						</li>
						<li>грамотно облаштоване комфортне робоче місце;</li>
						<li>відстрочку нострифікації диплома.</li>
					</ul>
					<p class="mb-5">
						Додайте до цього оптимальні умови для здобуття нових знань, професійного та кар'єрного
						зростання, а також можливість працювати, орієнтуючись на високі стандарти європейської
						медицини. А потім, оцінивши всі вигоди та переваги, звертайтеся - підберемо для вас
						найкращу вакансію.
					</p>
				</div>
			</div>
		</section>
	</main>
	<Footer />
</div>
